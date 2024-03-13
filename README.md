# 2c.SIMULATING ARP /RARP PROTOCOLS
## AIM
To write a python program for simulating ARP protocols using TCP.
## ALGORITHM:
## Client:
1. Start the program
2. Using socket connection is established between client and server.
3. Get the IP address to be converted into MAC address.
4. Send this IP address to server.
5. Server returns the MAC address to client.
## Server:
1. Start the program
2. Accept the socket which is created by the client.
3. Server maintains the table in which IP and corresponding MAC addresses are
stored.
4. Read the IP address which is send by the client.
5. Map the IP address with its MAC address and return the MAC address to client.
## PROGRAM - ARP
![Screenshot 2024-03-13 113403](https://github.com/Narasimhan05/2c.ARP_RARP_PROTOCOLS/assets/132819871/54b9641e-0628-4b71-847e-23ef2b38ed62)

## OUPUT - ARP
![Screenshot 2024-03-13 113431](https://github.com/Narasimhan05/2c.ARP_RARP_PROTOCOLS/assets/132819871/7d86373c-2083-426b-9e22-274ef0c8d072)

## PROGRAM - RARP
![Screenshot 2024-03-13 113410](https://github.com/Narasimhan05/2c.ARP_RARP_PROTOCOLS/assets/132819871/aeba1a0c-fe6f-43bc-8589-af3c06bb1e18)

## OUPUT -RARP
![Screenshot 2024-03-13 113440](https://github.com/Narasimhan05/2c.ARP_RARP_PROTOCOLS/assets/132819871/0551343f-309a-4db6-824d-27fee3dde630)

## RESULT
Thus, the python program for simulating ARP protocols using TCP was successfully 
executed.
