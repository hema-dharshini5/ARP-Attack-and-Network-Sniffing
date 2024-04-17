## Name : Hema dharshini 
## Register no: 212223220034

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

![1](https://github.com/hema-dharshini5/ARP-Attack-and-Network-Sniffing/assets/147117728/1898c434-7b48-4572-a155-c4d98ec33c5c)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![2](https://github.com/hema-dharshini5/ARP-Attack-and-Network-Sniffing/assets/147117728/79c3fe72-9ff3-4f05-ae4d-91a5755cb49e)

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:


![3](https://github.com/hema-dharshini5/ARP-Attack-and-Network-Sniffing/assets/147117728/869c19d7-12e6-42e3-b8ea-4fa28bfaa974)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![45](https://github.com/hema-dharshini5/ARP-Attack-and-Network-Sniffing/assets/147117728/6482327f-352b-482c-89ce-5ab21bc84d10)



Invoke the wireshark and examine the various menus  and controls of the tool:
![4](https://github.com/hema-dharshini5/ARP-Attack-and-Network-Sniffing/assets/147117728/55c1a138-49eb-4c75-9946-29f8d823588c)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
