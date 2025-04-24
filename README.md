# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
## Name: Gowtham N
## Reg no:212222220013
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

![image](https://github.com/user-attachments/assets/55bac14a-047d-48fa-9f00-dec5216553de)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/aacfffd4-3120-4e78-a5c8-9376b9cb9a38)


 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/b599367d-f0de-47bd-a53a-16bcbf1646f5)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/8521d34d-3d1d-48c2-bc72-8e2d945b8e1c)



Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/2b2d9f53-5c79-4aa3-9a1e-b653f062b707)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
