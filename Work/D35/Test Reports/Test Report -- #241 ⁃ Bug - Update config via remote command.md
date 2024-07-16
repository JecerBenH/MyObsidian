### Test case code in Request POST API /api/config/export Handler: 
![[Pasted image 20240619094236.png]]

Each time we press "Export Current Configuration" button, the above routine is executed :
1. local-config value is printed to terminal.
2. pid.json file is printed.
3. local_config_set_filename_value_by_key() parses on/off alternatively each time we press the button.
4. reloading config_manager.
5. logging new local_config value.

### Test Case execution: 
- "Export Current Configuration" Button pressed once : (ESP logs) ![[Pasted image 20240619095455.png]]
As we can see in the screenshot we can observe that local_config and pid.json are in sync and both pid(status) is off, then the value for local_config changed to true at the end of the routine.

- "Export Current Configuration" Button pressed another time : (ESP logs)![[Pasted image 20240619100103.png]]
- As shown in the screenshot above the value of local_config and pid.json changed successfully.



### Test Results:
| Tests Done | Test success | Test Fail |
| ---------- | ------------ | --------- |
| 22 Tests   | 22           | 0         |
For better result accuracy SD card (pid.json file) was checked every 3 tests.

