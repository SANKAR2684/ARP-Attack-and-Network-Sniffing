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
![Screenshot 2025-03-29 085624](https://github.com/user-attachments/assets/80c498ac-99eb-4f2e-8c17-99bcf3111f56)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![Screenshot 2025-03-29 090130](https://github.com/user-attachments/assets/7ae9843f-9c3c-4662-a635-d48f15f7b6c8)



 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![Screenshot 2025-03-29 092946](https://github.com/user-attachments/assets/7da389b6-a4a3-432c-affa-31ee5a42c0e2)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![Screenshot 2025-03-29 092914](https://github.com/user-attachments/assets/e44fd24f-6d73-4942-8eae-e3ab8232201a)




Invoke the wireshark and examine the various menus  and controls of the tool:
![Screenshot 2025-04-07 135439](https://github.com/user-attachments/assets/ddceb839-5c04-4ad8-ba8d-5d80ef0a275e)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
