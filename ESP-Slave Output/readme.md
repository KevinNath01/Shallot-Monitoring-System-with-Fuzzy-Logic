# ESP-Slave Output Configuration
In research the output it a water solenoid valve that can inject a certain amount of liquid into the irrigation system. The data is received from Raspberry Pi via ESP-Master. This set uses waterflow sensor too measure the amount of liquid injected into the system and solenoid valve to open/close the liquid flow.

Please look at this schematic for reference below :<br />
<img src="https://github.com/KevinNath01/Shallot-Monitoring-System-with-Fuzzy-Loggic/blob/main/Information/ESP-Slave Output.png" width=600 height=350>

Please change the parameter below :
1. Define Max Channel 11/13 according to your country (Line 13)
2. ESP-Master MAC Address (Line 21)
