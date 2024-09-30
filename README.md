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
![image](https://github.com/user-attachments/assets/d28f7511-2c61-440d-80aa-8794ddcd4aae)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/1a1da4f0-9612-455a-a3ea-1d05256d96f4)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/46e2ad0e-c145-4347-8842-e0af4cdebe75)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/5276d754-0832-4f7d-a0dc-71da519265a1)
Invoke the wireshark and examine the various menus and controls of the tool:
![image](https://github.com/user-attachments/assets/a9f15e29-61ce-4d04-ae6d-97c2a7fd05ee)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully







