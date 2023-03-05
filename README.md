# IP_and_mac_changer_bash

ifconfig wlan0 down
ifconfig wlan0 hw ether D2:73:0C:AE:30:8A
ifconfig wlan0 10.10.6.158
ifconfig wlan0 up
echo "ip and mac changed"
