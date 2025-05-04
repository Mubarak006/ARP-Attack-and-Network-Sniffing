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
![image](https://github.com/user-attachments/assets/84a17950-7662-4f65-8c87-4261c5603eaa)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/9c87f45f-a77c-44cd-963a-5cb34951b026)



 dsniff:







In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/11257748-ac1a-4a44-9289-a0f580e8f5c1)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/27b97d52-5ab6-4f88-865b-1c1977d1f87e)




Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/e2880899-0f14-4d22-b831-6952bf2121c3)

##Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis.
Ettercap can be used as sniffing tool as illustrated below:

![Uploading image.png…]()





## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
