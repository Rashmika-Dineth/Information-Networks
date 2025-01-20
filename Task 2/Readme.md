# Excercise 2

### IP ADDRESS EXERCISES

1. The IP addresses of devices and their subnet masks are shown below. Find out which part of
   the address is network and which part is host.

   - a) 192.168.6.25, 255.255.0.0
   - b) 170.10.0.15, 255.255.255.0
   - c) 10.10.10.1, 255.255.255.0

| #   | Network      | Host |
| --- | ------------ | ---- |
| a   | 192.168.     | 6.25 |
| a   | 255.255.     | 0.0  |
| --- | ----------   | ---- |
| b   | 170.10.0.    | 15   |
| b   | 255.255.255. | 0    |
| --- | ----------   | ---- |
| c   | 10.10.10.    | 1    |
| c   | 255.255.255. | 0    |
| --- | ----------   | ---- |

2. Which of the computers in the network below can operate with each other?
   ![](Images/image1.JPG)

   PC1 => Network part => 172.16 (No communications)
   PC2 => Network part => 175 => PC3
   PC3 => Network part => 175 => PC2
   PC4 => Network part => 172.18 => PC7
   PC5 => Network part => 192.168.5 (No communications)
   PC6 => Network part => 192.168.6 => PC8
   PC7 => Network part => 172.18 => PC4
   PC8 => Network part => 192.168.6 => PC6

3. The computer, "laptop" and mobile device in the picture are connected to the Internet via the router in the picture. The router's IP address is 172.18.226.1 and the subnet mask is 255.255.255.0.

   ![](Images/image2.JPG)

- a) What should the IP addresses and masks of terminal devices be like in order for Internet access to be possible?
- b) What kind of IP address should be defined as the default gateway for terminal devices

4. What is the first and last address available for devices on the networks below. Why?

- a) 192.0.0.0 ; 255.255.255.0
- b) 172.0.0.0 ; 255.255.0.0
- c) 112.0.0.0 ; 255.0.0.0
- d) 192.168.0.0 ; 255.255.0.0

5. Find out from your own computer:

- a) Your IP address
- b) Gateway IP address
- c) DNS server IP address
- d) DHCP server IP address
- e) Does your computer use a public or private IP address
