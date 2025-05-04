# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/1670a1f4-94c8-4dda-8c6e-1f3144e8e3ad)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/151d9924-056e-4b0b-b8f3-ae2c76eb1538)


 dsniff:





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/74e0aa4e-98b4-4fcc-acd0-6fee9f71caf8)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/89570218-9c85-4220-9f63-65553d12e460)




Invoke the wireshark and examine the various menus  and controls of the tool:


![image](https://github.com/user-attachments/assets/ca5b3191-0e16-4def-a7b0-735cc8f357ce)

## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:
![image](https://github.com/user-attachments/assets/65175dec-d7de-46d0-ad3f-bbfaf266b9e5)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
