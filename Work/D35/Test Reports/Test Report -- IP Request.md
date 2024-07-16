# Test 1 : 
No delay introduced in between network_connect() and pppos_setup().
### Setup:
- 3.6V & Up to 5A on modem VCC using external power supply
- modem APN configured to "internet.tn"
- Code checked out at commit "rework modem at test" 6335260cab8de5d2ee7b0bc5b49744fca4ca35e4
### Results:

IP Request success : 1 , fails : 42.

![[Pasted image 20240507135712.png]] [..+CESQ: 13,99,255,255,255,255....OK..]

# Test 2 (Voltage change):
No delay introduced in between network_connect() and pppos_setup().
### Setup:
- 3.8V & Up to 5A on modem VCC using external power supply
- modem APN configured to "internet.tn"
- Code checked out at commit "rework modem at test" 6335260cab8de5d2ee7b0bc5b49744fca4ca35e4
### Results:
IP Request success : 2 , fails : 49.

![[Screenshot 2024-05-07 140407.png]]
[..+CESQ: 15,99,255,255,255,255....OK..]

# Test 3 :
No delay introduced in between network_connect() and pppos_setup().
### Setup:
- 3.8V & Up to 5A on modem VCC using external power supply
- modem APN configured to "internet.tn"
- Code checked out at commit "to be tested" on branch "2GPPPRETRY"
  f677d7ba60f5ec286337b723be5da52279d35497
### Results:

IP Request success : 0 , fails : 16.

