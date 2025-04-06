<h1>Creating a Windows VM (Azure)</h1>
This tutorial outlines initial set up of my home lab using VMs in Azure. My set-up at the time was unable to run a hypervisor like VirtualBox, so this Azure has been my go to on my other projects. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- VirtualBox

<h2>Operating Systems Used </h2>

- Windows 11

<h2>Deployment and Configuration Steps</h2>

<p>
One of the most convenient ways to setting up a Windows VM is using the cloud. This will allow you to remotely connect to a desktop and run Windows (in this case)  or many other VMs. I am going to use a free account on Microsoft Azure to do this.

This method was way more accessible than running a hypervisor like VirtualBox due to the limitations of my laptop, and provided an easy, flexible solution to create VM instances to start learning.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
The first step is to go to the Microsoft Azure account and make a free account. You can use a new or existing Microsoft account.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Disclaimer here, Azure will require a credit card to be put onto your account. Azure does give you a $200 credit for the first 30 days of your account, which is more than enough. (My instance of Windows 11 has an estimated cost of about $0.07/hour and that is if I left it running all day and night)

Now let's create a virtual machine. There is no need to download any applications or ISO files with this method. It is easy to see why cloud computing is gaining popularity.

Click the dropdown menu at the top left corner of the main page and click "Create a resource."
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
I am using Windows 11 and for the sake of this demo I will use Windows 11 preview.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Set a name for your virtual machine and pick a region. Ideally you would choose a location closer to you for less latency but you could have different needs.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
On the same page scroll down and set an admin username and password that you will use to gain remote access to your VM later.

There are more tabs with many more customizable options. For the sake of this practice I will skip over these and click "Create" on the last tab.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Azure might take a few minutes to deploy your machine once finished you will connect and download your RDP file which is used to establish a remote connection.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
This is where the admin account you made will come in hand, click "More choices" and enter those admin details and you will have access to your VM through Azure.

After clicking through a few prompts and verifying you are the user trying to access remote desktop you should be set. You are now running Windows 11 in the cloud.
</p>
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Have fun exploring but remember to watch your resource usage. The "Cost Management" tab will help you keep track of any spending you may do and it also allows you to set up budget alerts.
</p>
<br />
