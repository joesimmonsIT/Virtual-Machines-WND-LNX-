<p align="center">
<img src="https://i.imgur.com/wASub3v.png"/>
</p>

<h1> Creating Virtual Machines for Windows 10 & Linux (Ubuntu) in Microsoft Azure </h1>
This tutorial outlines the creation and confirmation of Virtual Machines for Windows 10 and Linux (Ubuntu) within Azure Virtual Machines.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Linux (Ubuntu) 

<h2>High-Level Deployment and Configuration Steps</h2>

- Azure Portal
- Resource Group
- Windows 10 Virtual Machine
- Linux (Ubuntu) Virtual Machine
- Confirmation

<h2>Azure Portal</h2>

<p>
<img src="https://i.imgur.com/7R4f1BV.png"/>
</p>
<p>
Open a new internet browser and go to: Portal.Azure.com. <br /> <br />
Log into your account if you are not already logged in.
</p>
<br />

<h2> Resource Group </h2>
<p>
<img src="https://i.imgur.com/SN2IgER.png"/>
</p>
<p>
In the search box type "Resource group" and select "Resource groups" from the search results.
</p>
<br />

<p>
<img src="https://i.imgur.com/mldlnqP.png"/>
</p>
<p>
Select the "Create" button in the middle of the page.
</p>
<br />

<p>
<img src="https://i.imgur.com/dEAfMVd.png"/>
</p>
<p>
For the subscription select the appropriate subscription, if you have more than one Microsoft Azure subscription. <br /> <br />
If you only have one subscription skip this step and proceed to the next step. <br /> <br />
For the Resource Group select the desired name, in this tutorial we will be using "RGLab02". <br /> <br />
For the Region select the desired region, in this tutorial we will be using "(US) East US 2". <br /> <br />
Select Review + Create to continue with creating the Resource Group. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/46UInEk.png"/>
</p>
<p>
Once all the steps are completed correctly you should see a green checkmark and the words "Validation passed". <br /> <br />
Select the "Create" button at the bottom to proceed with the creation of the Resource Group. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/DJRnZ6S.png"/>
</p>
<p>
We will be taken to the Resource Group Home Page where we will see our newly created Resource Group "RGLab02".  
</p>
<br />

<h2>Windows 10 Virtual Machine</h2>
<p>
<img src="https://i.imgur.com/Kr53dxe.png"/>
</p>
<p>
Go to the URL and type: Portal.Azure.com. <br /> <br />
In the search bar type "Virtual Machines". <br /> <br />
Select Virtual Machines from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/v5bbZ2n.png"/>
</p>
<p>
Select the + Create button. <br /> <br />
Select Azure virtual machine from the drop down menu. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/SG9hg76.png"/>
</p>
<p>
For the Subscription select the approriate subscription if you have more than one Microsoft Azure subscription. <br /> <br />
If you only have one subscription skip this step and proceed to the next step. <br /> <br />
For the Resource Group select the desired name, for this tutorial we will be using "RGLab02". <br /> <br />
Virtual Machine Name: VM1. <br /> <br />
For the Region select the desired region, in this tutorial we will be using "(US) East US 2". <br /> <br />
For the Zone select the desired zone, in this tutorial we will be using Zone 1. <br /> <br />   
</p>
<br />

<p>
<img src="https://i.imgur.com/7lIMRIC.png"/>
</p>
<p>
For the Image select the desired image, for this tutorial we will be using "Windows 10 Pro".
</p>
<br />

<p>
<img src="https://i.imgur.com/3gpSV70.png"/>
</p>
<p>
Size: Select "Standard 2 vcpus". <br /> <br />
Username: labuser. <br /> <br />
Password: Create a password (minimum 12 characters including special characters) you can remember or easily write down to retrieve easily. <br /> <br />
Confirm Password: Repeat the same password you previous entered in the previous step. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/lzXLxeY.png"/>
</p>
<p>
Acknowledge the Licensing Confirmation by check the box, it should turn blue. <br /> <br />
Select Review + Create to proceed with creating the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/VU73IBv.png"/>
</p>
<p>
Once all the steps have been completed correctly you should see a green check mark and the words "Validation passed." <br /> <br />
Select "Create" to proceed with the creation of the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/9FCJ4nr.png"/>
</p>
<p>
The deployment (creation) of the virtual machine is in process to be completed.
</p>
<br />

<p>
<img src="https://i.imgur.com/NhaTBh6.png"/>
</p>
<p>
The creation of the virtual machine is completed.
</p>
<br />

<h2>Linux (Ubuntu) Virtual Machine</h2>
<p>
<img src="https://i.imgur.com/Kr53dxe.png"/>
</p>
<p>
Go to the URL and type: Portal.Azure.com. <br /> <br />
In the search bar type "Virtual Machines". <br /> <br />
Select Virtual Machines from the search results. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/v5bbZ2n.png"/>
</p>
<p>
Select the + Create button. <br /> <br />
Select Azure virtual machine from the drop down menu. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/fE44w9V.png"/>
</p>
<p>
For the Subscription select the approriate subscription if you have more than one Microsoft Azure subscription. <br /> <br />
If you only have one subscription skip this step and proceed to the next step. <br /> <br />
For the Resource Group select the desired name, for this tutorial we will be using "RGLab02". <br /> <br />
Virtual Machine Name: VM2. <br /> <br />
For the Region select the desired region, in this tutorial we will be using "(US) East US 2". <br /> <br />
For the Zone select the desired zone, in this tutorial we will be using Zone 1. <br /> <br />  
</p>
<br />

<p>
<img src="https://i.imgur.com/HLwS3TE.png"/>
</p>
<p>
For the image select the desired image, for this tutortial we will be using "Ubuntu Server 20.04 LTS".
</p>
<br />

<p>
<img src="https://i.imgur.com/y3NR7R0.png"/>
</p>
<p>
Size: Select "Standard 2 vcpus". <br /> <br />
Authentication Type: Select Password. <br /> <br />
Username: labuser. <br /> <br />
Password: Create a password (minimum 12 characters including special characters) you can remember or easily write down to retrieve easily. <br /> <br />
Confirm Password: Repeat the same password you previous entered in the previous step. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/VfB20UZ.png"/>
</p>
<p>
Select Review + Create to proceed with creating the Linux (Ubuntu) virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/3U8Uab5.png"/>
</p>
<p>
Once all the steps have been completed correctly you should see a green check mark and the words "Validation passed." <br /> <br />
Select "Create" to proceed with the creation of the virtual machine. <br /> <br />
</p>
<br />

<p>
<img src="https://i.imgur.com/SuAWyAs.png"/>
</p>
<p>
The deployment (creation) of the virtual machine is in process to be completed.
</p>
<br />

<p>
<img src="https://i.imgur.com/J9Ro46J.png"/>
</p>
<p>
The creation of the virtual machine is completed.
</p>
<br />

<h2>Confirmation </h2>
<p>
<img src="https://i.imgur.com/8IvMJLM.png"/>
</p>
<p>
Go to URL: Portal.Azure.com <br /> <br />
Select the Virtual Machines icon. <br /> <br />
You should see the Windows and Linux (Ubuntu) Virtual Machines we previously created. <br /> <br />
Congratulations you have completed this tutorial successfully! <br /> <br />
</p>
<br />
