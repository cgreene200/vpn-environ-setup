


![alt text]( https://i.imgur.com/9mB6LIu.png)
# **Exploring VPN Technology in a Virtual Environment**
### This tutorial walks through the basics of VPN Technology and documents the steps used to setup a secured VPN tunnel connection in an Azure virtual environment.


## Environments and Technologies Used

*  My Personal Laptop
*  Microsoft Azure (Virtual Machines)
*  Remote Desktop
*  ProtonVPN Software

## Operating Systems Used

* Windows 10

## What this exercise will show?


 1. Find my laptop's IP address and location via www.whatsmyipaddress.com
 2. Start a remote desktop session on a virtual machine created in Microsoft Azure
 3. Find the virtual machines's IP address and location via www.whatsmyipaddress.com
 4. Create an account in ProtonVPN, install ProtonVPN and select a server and location
 5. Find the ProtonVPN IP address and location via www.whatsmyipaddress.com
 
 
 
![alt text](https://i.imgur.com/O43f56y.png)

### The above image focuses on the area between My Actual PC and Public Websites
To start the exercise, I had to Find the public IP address and location on my laptop by using www.whatsmyipaddress.com, as shown above.



![alt text](https://i.imgur.com/5uPl7bZ.png)

### The above image focuses on the pink area between My Actual PC and the Azure VM.
After creating the Azure virtual machine, find the **IP address** and the **location** by going to www.whatsmyipaddress.com. After finding this information, create a remote desktop session from this virtual machine. as shown above.


![alt text](https://i.imgur.com/WigkWnh.png)


### The above image focuses on the green area between the Azure VM and the ProtonVPN server. The steps that follow take place in this section of the image.
In this section, the **remote desktop** has been created and it is from this VM that we will start working with the VPN environment.  We went to www.protonvpn.com to create an account.  Once the account has been created, we need to download the ProtonVPN client and install it on the remote desktop session  that was created.

### Create an Account with www.ProptonVPN.com


![alt text](https://i.imgur.com/JFP8qZs.png)
 ![alt text](https://i.imgur.com/Uiy65cB.png)

### Sign into your ProtonVPN account as shown below.

![alt text](https://i.imgur.com/Sq6ufX8.png)

### Download and install the ProtonVPN application

![alt text](https://i.imgur.com/B8AxcqM.png)


![alt text](https://i.imgur.com/q3cI5Wx.png)


![alt text](https://i.imgur.com/FuK6xSn.png)


### Launch ProtonVPN and login to your ProtonVPN account

![alt text](https://i.imgur.com/mWVdzjQ.png)

### Choose a VPN Server and Country location


![alt text](https://i.imgur.com/R7fbVJu.png)


### Connecting to the chosen Netherlands server 


![alt text](https://i.imgur.com/wChc9Pv.png)


### Connected to the chosen Netherlands server


![alt text](https://i.imgur.com/HNu7TYV.png)

### Ok!...now we're connected to a VPN tunnel.  What does that mean and what are some of the benefits of this connection? 
Right now, our current IP address and location is encrypted and secured. 

### Now, let's test our VPN connection by opening a refreshed browser session, as shown below.
We can now see the localization features in our browser. Letting us know that Google has now taken on features of the Netherlands, as shown below.

![alt text](https://i.imgur.com/iPNBpr0.png)


