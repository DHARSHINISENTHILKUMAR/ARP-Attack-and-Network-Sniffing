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


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:
![image](https://github.com/user-attachments/assets/25cbb0c2-d5e9-47d1-9326-fac5063f70aa)






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/bfa830be-a382-4734-9800-e380465ec279)
![image](https://github.com/user-attachments/assets/a9da5965-3bf9-4103-9f00-1d9db1a8b86c)




In Kali issue the following commands:
sudo dsnifff

## OUTPUT:
![image](https://github.com/user-attachments/assets/20bc450f-ed85-4505-968b-812d2c5d103f)
![image](https://github.com/user-attachments/assets/462ef57f-7e60-4012-8da8-54ef5c51be89)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
