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
### OUTPUT:
![image](https://github.com/user-attachments/assets/c9f6fd3a-0a9b-405f-867e-9cff110e546c)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>


### OUTPUT:

![image](https://github.com/user-attachments/assets/fc2b4603-f6d8-4621-b277-fc58ca50fdf1)

###  dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
### OUTPUT:

![image](https://github.com/user-attachments/assets/78eb31f6-778d-47ca-8465-56cdaf07418f)



In Kali issue the following commands:
sudo dsnifff
### OUTPUT:

![image](https://github.com/user-attachments/assets/0643882b-984c-495e-b207-48169caff049)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/e4aaf9b1-a726-459e-9b07-8f769fef352d)



### RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
