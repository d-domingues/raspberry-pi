// raspbery ip address
ip addr (inet)

// set static ip address
https://www.youtube.com/watch?v=S-VnPDECtog
config file at etc/dhcpcd.conf

// check your local networks LAN ips:
run cmd:
ipconfig

// ping all the decices in your network to check which ones are connected to your LAN
create new file "ips-list.txt"
cd to dir where the fie was created
run the cmd: ()
for /L %i in (0,1,255) do ping -n 1 -w 25- 192.168.0.%i>>ip-list.txt
(make sure to check the same router adress group 192.168.0.X or 192.168.1.X)

// configure VNC
tutorial frenove page 20
