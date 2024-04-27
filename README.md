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

![image](https://github.com/Srujana0303/ARP-Attack-and-Network-Sniffing/assets/132996836/927d5271-208b-4ea2-ad85-77e171e9de81)

From Kali linux issue the command : sudo arpspoof -i etho -t

![image](https://github.com/Srujana0303/ARP-Attack-and-Network-Sniffing/assets/132996836/b949198d-84eb-42f3-9750-c0ffb5cd8903)

 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![image](https://github.com/Srujana0303/ARP-Attack-and-Network-Sniffing/assets/132996836/d7b3a692-7df9-4774-adc6-22b9e021167c)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/Srujana0303/ARP-Attack-and-Network-Sniffing/assets/132996836/abd283b1-fd55-4fc2-8aa9-90b9b8ea993a)

Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/Srujana0303/ARP-Attack-and-Network-Sniffing/assets/132996836/f99f652e-7f64-4341-b9eb-4d63800e0d3f)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
