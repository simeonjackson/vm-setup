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

![Screenshot 2025-01-31 030345](https://github.com/user-attachments/assets/a3790c7a-8b69-4b47-b712-d6a6952cac53)



<p>
The first step is to go to the Microsoft Azure account and make a free account. You can use a new or existing Microsoft account.
</p>

![Screenshot 2025-01-31 123107](https://github.com/user-attachments/assets/b740c1d7-3a5d-4ef5-a176-9de995b3f4ae)



<p>
Disclaimer here, Azure will require a credit card to be put onto your account. Azure does give you a $200 credit for the first 30 days of your account, which is more than enough. (My instance of Windows 11 has an estimated cost of about $0.07/hour and that is if I left it running all day and night)

Now let's create a virtual machine. There is no need to download any applications or ISO files with this method. It is easy to see why cloud computing is gaining popularity.

Click the dropdown menu at the top left corner of the main page and click "Create a resource."
</p>

![Screenshot 2025-01-31 124407](https://github.com/user-attachments/assets/4d5f269e-41ee-4581-84a7-01c8b1ba0940)



<p>
I am using Windows 11 and for the sake of this demo I will use Windows 11 preview.
</p>

![Screenshot 2025-01-31 124507](https://github.com/user-attachments/assets/0b23f872-3c71-4a34-84f0-c7f4ceda2e7e)



<p>
Set a name for your virtual machine and pick a region. Ideally you would choose a location closer to you for less latency but you could have different needs.
</p>

![Screenshot 2025-01-31 124918](https://github.com/user-attachments/assets/bf19d5a0-0ce8-447c-9bcb-66245d41ad41)


<p>
On the same page scroll down and set an admin username and password that you will use to gain remote access to your VM later.

There are more tabs with many more customizable options. For the sake of this practice I will skip over these and click "Create" on the last tab.
</p>

![Screenshot 2025-01-31 130721](https://github.com/user-attachments/assets/ec086f69-0ae7-4d9c-8989-f5f25fc035d2)

![Screenshot 2025-01-31 131139](https://github.com/user-attachments/assets/02692d55-2f63-4833-bc43-d4f5da1d227b)


<p>
Azure might take a few minutes to deploy your machine once finished you will connect and download your RDP file which is used to establish a remote connection.
</p>

![Screenshot 2025-01-31 131447](https://github.com/user-attachments/assets/483eec52-e974-4d7a-9e9a-90d6403576a3)


<p>
This is where the admin account you made will come in hand, click "More choices" and enter those admin details and you will have access to your VM through Azure.

After clicking through a few prompts and verifying you are the user trying to access remote desktop you should be set. You are now running Windows 11 in the cloud.
</p>

![Screenshot 2025-01-31 132040](https://github.com/user-attachments/assets/5155cf4b-cf43-4589-80b3-fe722db455bd)


<p>
Have fun exploring but remember to watch your resource usage. The "Cost Management" tab will help you keep track of any spending you may do and it also allows you to set up budget alerts.
</p>
<br />
