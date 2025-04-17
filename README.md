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

![image](https://github.com/user-attachments/assets/5d8edaa4-0c7e-4931-b2d7-f8daad4ce2bb)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

![image](https://github.com/user-attachments/assets/317e1f47-ea21-4504-87b2-d46fccbd7c59)

 dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![image](https://github.com/user-attachments/assets/37258d59-fb7d-45b9-b35c-0cc0e965a34e)


In Kali issue the following commands:

sudo dsnifff

## OUTPUT:

![image](https://github.com/user-attachments/assets/506a5009-d739-4cc4-a8ec-93dc81fb04a2)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/20e876b3-836e-4685-9200-681c60619b28)


## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully
