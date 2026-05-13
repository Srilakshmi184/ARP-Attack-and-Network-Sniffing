<img width="637" height="343" alt="image" src="https://github.com/user-attachments/assets/7f876c64-e7fe-44ca-98b2-d29945c1d8c7" /># ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
# NAME-SRILAKSHMI BH
# REG.NO-212224100057 
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

<img width="856" height="738" alt="image" src="https://github.com/user-attachments/assets/c8cb8187-fd96-40ba-8ca7-10b16b43de2d" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="637" height="343" alt="image" src="https://github.com/user-attachments/assets/f4efefe2-4d55-48f4-a1fc-a49720760921" />


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
