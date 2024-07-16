1. The D35 device needs to be subscribed to another D35/D12 device through the Link2Valves website. ​
2. The subscriber device should be physically configured (via R-UI) to read a channel from an available Link2Valves publisher as a local variable. ​
3. The subscriber device should activate a mechanism within R-Engine that periodically makes requests to the peering endpoint of Link2Valves HTTP API to retrieve the latest value to apply to the created local variable(s). ​
4. (Optional) The publisher device can be physically configured (via R-UI) to activate an additional data transfer mechanism optimized for peering. ​ This mechanism only transmits the latest measurement for every channel, saving bandwidth, but does so more frequently than the normal data transfer to ensure timely updates for the subscriber. ​

In terms of interfaces for the D35 device:

1. The main configuration section for "http peering" would be under Remote Recopy. ​
2. The Publishing / Subscriptions selection should be available when in HTTP mode. ​

For the Publisher interface on the D35 device:

1. HTTP peering works when Link2Valves is selected as the cloud storage. ​
2. Enabling publishing starts an internal timer with the configured refresh time. ​ After every refresh interval, the device makes a POST LATEST DATA request to Link2Valves. ​
3. The import button and the Subscribers tab are not needed for HTTP peering. ​
4. None of the settings modify the normal transfer interval of the full data log file. ​

For the Subscriber interface on the D35 device:

1. HTTP peering works when Link2Valves is selected as the cloud storage. ​
2. The "subscriptions" list should only show the list of available publishers for the selected mode. ​
3. Closed Loop subscriptions or available publishers should not be shown in the Remote Recopy lists. ​
4. The HTTP list screen should include a refresh button to repopulate the list via a Link2Valves request. ​
5. If no publishers are found for HTTP peering, a warning message should appear. ​
6. Clicking on a publisher should bring up the "refresh interval" menu screen. ​
7. The "Track changes" checkbox is not needed and is considered always ON. ​
8. A test button should be available to verify the connection to the publisher. ​ This button should perform both a GET LIST OF CHANNELS request for the selected device and a GET LATEST DATA request. ​ If any of them fail, a message should describe what happened. ​
9. When the TEST button is used, the publisher data refresh interval should be updated. ​
10. The "Channel Use" tab should display a list of the current local variables that have been overridden by remote recopies. ​
11. A "trash" button should allow removing the selected variable override. ​
12. An "add" button should show a pop-up to add a new local override with data coming from the publisher. ​
13. The options for "Source value" should be taken from the GET LIST OF CHANNELS request for the selected publisher. ​
14. Overrides set up this way should be displayed normally in the screens that show the input values, just like any manual override would. ​

In terms of requests for the D35 device:

1. The D35 device can make a GET request to the endpoint "[https://www.link2valves.com/api/devices/{imei}/peering/publishers](https://www.link2valves.com/api/devices/%7Bimei%7D/peering/publishers)" to get the list of available publishers. ​
2. The D35 device can make a GET request to the endpoint "[https://www.link2valves.com/iot/devices/{imei}/peering/publishers/{publisherImei}](https://www.link2valves.com/iot/devices/%7Bimei%7D/peering/publishers/%7BpublisherImei%7D)" to get the list of channels from a specific publisher. ​
3. The D35 device can make a GET request to the endpoint "[https://www.link2valves.com/api/devices/{imei}/peering/latest-data/{channelIds}](https://www.link2valves.com/api/devices/%7Bimei%7D/peering/latest-data/%7BchannelIds%7D)" to get the latest data from publishers for specific channels. ​
4. The D35 device can make a POST request to the endpoint "[https://www.link2valves.com/api/devices/{imei}/peering/latest-data](https://www.link2valves.com/api/devices/%7Bimei%7D/peering/latest-data)" to send the latest data for subscribers.