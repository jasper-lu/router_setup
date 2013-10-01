Step 1: Run init if you don't already have all of the necessary files. If it has been a while since you last copied over the files, run init anyway.

Step 2: Turn off your wireless

Step 3: Flash the router with the OpenWrt firmware (ends in factory.bin)
at 192.168.0.1

Step 4: Telnet into the router using the command "telnet 192.168.1.1" 

Step 5: Change the router's defaul ip from 192.168.1.1 to 192.168.5.1 using the command "uci set network.lan.ipaddr=192.168.5.1" and then "uci commit." Verify that it is correct and use the command "reboot."

Step 6: Run the flash script (./flash)
