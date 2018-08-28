## Assignment for PIPE and FIFO ##

# Task

* [ ] Write Linux C program to create two processes P1 and P2. P1 Needs to read network parameters like IP/NETMASK/gateway/DNS address of WiFi/Ethernet interface of your laptop and passes it to P2 as per user selection. P2 concatenates the received address from P1 with your laptop username and needs to print the string.

* [ ] Output string should be in below format.  
     username:parameter-name:address 
     Eg: vkchlt0116:IP:192.168.239.70 : when user select IP
     
     vkchlt0116:NETMASK:255.255.255.0 : when user select NETMASK
#Attached code
``process1.c``:program to read network parameters like IP/NETMASK/GATEWAY/DNS address of WiFi/Ethernet interface

``process2.c``:program to concatenates the received address from P1
