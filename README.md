![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/7813a688-9490-4850-bdff-89177b8e085b)

# Creating-a-Virtual-Private-Network-on-Azure-VM
In this lab we will set up a VPN using ProtonVPN on an Azure VM. We will connect to the VM using Remote Desktop.

## Prerequisites
1. Create an Azure Subscription to access the Azure Platform. This comes with an initial $200 credit for new accounts.

<h2>Environments and Technologies Used</h2>
(NOTE: I was able to set up the entire project on both my IPAD Pro 2020 and Desktop

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop/RD Client
- PROTONVPN
- WHATISMYIPADDRESS.COM


<h2>Operating Systems used</h2>

- windows 10(21h2)
- IpadOS Version 16

## Open Whatismyipaddress
1. In order to begin, we will open [https://www.whatismyip.com]
2. Verify Current IP address for your region (Write down if needed to compare IP addresses later)

## Virtual Machines (VM)
1. Navigate to “Virtual Machines”
2. Click “+ Add” to create a new Virtual Machines.
3. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Create or select.(for this VM i let the VM create its own)
   - Virtual Machine name: Enter a unique name.
   - Region: Choose the deployment region.(for this excercise we must select a region thatoutside of the one you are currently in)
4. Proceed to Create/Review.
5. Create a username and password in order to log in to the VM when using Remote Desktop.
6. Create the Virtual Machine.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/3a2baf83-9253-4cda-810c-638bb234791c)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/ee907031-0c09-426f-be74-b7dc3878cee1)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/952b0b4d-35db-4fa7-b5eb-b69719888e21)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/726c6b5a-c4dc-4e49-ab78-d130428e5d8c)

## REMOTE DESKTOP
1. Open Azure VM Overview and copy the IP address.
2. Open Remote Desktop (On Ipad open RD Client)
   - Add PC and input the IP address of the VM.
   - Remote Desktop will ask you to input password created for the VM Domain.
   - Privacy settings for the VM will pop up, Select NO for all.
5. Open Browser and enter [https://www.whatismyip.com]
   - NOTE: this should show the random IP address for the region selected for your VM.

![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/24766283-8b69-4efe-9fab-f6da43684e01)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/60ecf99a-d0c2-4227-96bf-687e18db6d9c)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/618698a1-f10d-40d3-9d73-f62851bbf67d)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/156940d6-db59-4fe6-84ae-a16f2514ed30)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/d12bc403-b44c-4845-b010-6f3d80c27c05)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/55b0896c-3da6-4540-a895-ebdb5f7856df)

## Setting up PROTONVPN
1. Open a new tab on VM browser and pull up PROTONVPN website.
   - Download VPN.
   - Proceed through and Install VPN.
2. Once installed open the ProtonVPN.
   - Connect with free options and random region will be selected for the VPN.
3. Open [https://www.whatismyip.com] and new region IP address should show if done correctly.
   - To Confirm new region, try opening google on new tab. (Native Region Language will reflect on google page)

![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/042662c1-82f0-4cf4-9784-109ac34592c7)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/849c4c59-439a-48a8-8112-2063f137f534)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/cec4c165-f213-4a40-9e1e-1f49c78b6adc)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/ffa3acee-07b0-47d9-91ad-edf67d158306)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/4645082f-fdb1-4ceb-8180-f6f5e750c89f)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/427e2c07-6e9d-433d-a41e-413454c43285)


-------------------

## Delete Resources/VM's at the End
1. Make sure to log back into Azure after the lab to Delete the Resource group and VM's.
   - This will ensure no unnecessary charges acrue for forgetting to delete lab.

![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/98806ffa-c56b-4f0e-983b-ae204b836b82)
![image](https://github.com/Richan21/Creating-a-Virtual-Private-Network-on-Azure-VM/assets/153684298/cdfb5b57-9b61-4b8e-a06a-7393e0a84d87)



## Note
- Configuration: The configurations set for this VM creating Lab will not work for eveything. Please adjust variables and configurate settings to fit your needs.
