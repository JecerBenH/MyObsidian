### Step 1: Understand the Current HTTP Peering Mechanism

Review the current implementation details of HTTP peering on D22/D12 devices via the Link2Valves gateway. Key components include:

1. **Publisher Configuration**
    - Uses HTTP to push data to Link2Valves.
    - Internal timer to send data at set intervals.
2. **Subscriber Configuration**
    - Devices subscribe to publishers and periodically request data.
    - Mechanism to handle subscriptions, data fetching, and updates.
3. **API Endpoints and Requests**
    - Getting list of publishers.
    - Getting list of channels.
    - Getting latest data.
    - Sending latest data.

### Step 2: Define Requirements for D35

Identify what needs to be replicated or modified for the D35 device:

1. **HTTP Peering Workflow** similar to D22/D12.
2. **Publisher and Subscriber Configurations** adapted for D35.
3. **Interface Adjustments** for X-Website instead of R-UI.

### Step 3: Design the Interface on X-Website

Ensure that the X-Website supports the following:

1. **Publisher Settings**:
    - Enable HTTP peering and set data refresh intervals.
    - Display list of subscribed devices.
2. **Subscriber Settings**:
    - List available publishers for subscription.
    - Configure refresh intervals and override local variables with remote data.
    - Test connection to publishers.
3. **Data Handling**:
    - Implement mechanisms for sending and receiving latest data.

### Step 4: Develop API Endpoints

Adapt or create new API endpoints on Link2Valves to support D35 devices:

1. **List of Publishers**:
    - GET /api/devices/{imei}/peering/publishers
2. **List of Channels**:
    - GET /api/devices/{imei}/peering/publishers/{publisherImei}
3. **Fetch Latest Data**:
    - GET /api/devices/{imei}/peering/latest-data/{channelIds}
4. **Send Latest Data**:
    - POST /api/devices/{imei}/peering/latest-data

### Step 5: Implement and Test

1. **Develop**:
    - Implement the necessary software changes on the D35 device firmware to handle HTTP peering.
    - Update X-Website interface with new configurations for publishers and subscribers.
2. **Test**:
    - Conduct thorough testing to ensure D35 devices can correctly publish and subscribe to data using HTTP peering.
    - Test the API endpoints with various scenarios to ensure reliability and performance.

### Step 6: Documentation and Training

1. **Update Documentation**:
    - Document the new features and configurations for D35 devices.
    - Provide detailed guides on setting up and managing HTTP peering via X-Website.
2. **Training**:
    - Train relevant personnel on the new features and how to use them.
