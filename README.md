# Installing VirtualBox and Windows Server 2022

The objective of this lab is to install VirtualBox so that we can create a Virtual Machine for Windows Server 2022 and ultimately install Active Directory and explore other IT tools!  

## Technologies Used

- VirtualBox
- Windows Server 2022

## Installation Steps  

### Downloading VirtualBox and Windows Server 2022

Head over to the [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads) page. Select the proper platform for your local machine. For this lab we will be downloading the Windows hosts version.  

<img src="https://i.imgur.com/GGQcJ3O.png" height="70%" width="70%" alt="VirtualBox downloads"/>

It is also recommended to download the VirtualBox Extension pack which gives support to VirtualBox RDP, dis encryption, NVMe and PXE boot for Intel cards.  

<img src="https://i.imgur.com/dePL6vK.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Now that we have VirtualBox downloaded, let's download Windows Server 2022!

In order to do so google "Windows Server 2022 Evaluation". This should result in a Microsoft page with Windows Server 2022 available for download. Click Download the ISO. 

<img src="https://i.imgur.com/qT3o1J1.png" height="70%" width="70%" alt="VirtualBox downloads"/>

After clicking "Download the ISO", it should bring you to a page for you to enter your information in order to get your free trial. If you do not wish to give your actual information, you can put anything in it's place. After you click "Download now", it will bring you to another page where you can download the ISO.

<img src="https://i.imgur.com/940u3Xb.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://i.imgur.com/UN8HeoT.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Now that we have VirtualBox and Windows Server 2022 downloaded, let's install and set things up!  

## Installing VirtualBox  

Navigate to the file location of your downloads and double click the VirtualBox setup wizard. Click Next and Yes where appropriate to install VirtualBox.  

<img src="https://imgur.com/T05BGYo.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://imgur.com/BRFJn1g.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://imgur.com/OHNBjES.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://imgur.com/jt9krfi.png" height="70%" width="70%" alt="VirtualBox downloads"/>

After the final Next, VirtualBox should be successfully installed! Launch it and you will be taken to the VirtualBox Manager

<img src="https://imgur.com/eMlnGjD.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Now that we have VirtualBox installed, let's set up a Windows Server 2022 Virtual Machine!

## Windows Server 2022 Configuration

On the VirtualBox Manager, click "New" in order to create a new Virtual Machine. A window should appear where we can name our Virtual Machine, specify a folder path, and load our ISO image of Server 2022.

<img src="https://i.imgur.com/Qf3BiSO.png" height="70%" width="70%" alt="VirtualBox downloads"/>

We will name this Virutal Machine "Server 2022 Lab". Place the VM in a folder path you are satisfied with then for ISO Image, click the arrow to open the drop down menu and click "Other". Navigate to the ISO we downloaded earlier and select it. Finally make sure the "Skip Unattended Install" is checked and click Next to continue.

<img src="https://i.imgur.com/by3kmLi.png" height="70%" width="70%" alt="VirtualBox downloads"/>

As you can see below, here we can specify the amount of memory and CPUs to provide the Virtual Machine. For the purposes of this lab we will allocate 4 GB of memory and 2 CPUs. The amount may differ depending on your local machine's specifications. Click Next when ready.

<img src="https://i.imgur.com/iCppK4m.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Here you can specify the amount of Hard Disk for the Virtual Machine. We will leave it at 50 GB as this will be more than enough for our purposes.

<img src="https://i.imgur.com/HB9MiiU.png" height="70%" width="70%" alt="VirtualBox downloads"/>

The Summary should look something similar to this. If everything looks good, click Finish to complete our Virtual Machine.

<img src="https://i.imgur.com/t3eK8a2.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Our Virtual Machine has been created but there is one last step; Windows Server 2022 Setup! 


## Windows Server 2022 Setup

Back in the VirtualBox Manager, we can see our VM now populated on the left hand side. Click the VM and then click Start in order to boot up the virtual machine.

<img src="https://i.imgur.com/RAzhcPt.png" height="70%" width="70%" alt="VirtualBox downloads"/>

The VM will begin to boot up and a new window will appear. Here we can begin the setup process for Windows. Select the appropriate language, click Next, then Install Now.

<img src="https://i.imgur.com/kXjyonN.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://i.imgur.com/h8wfbDr.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Below you can see multiple options for our Operating System. The one we want to select is the Standard Evaluation (Desktop Experience) version. This will allow us to use an actual Windows Desktop GUI for our server as opposed to a Non-Desktop experience which would only provide us a command line terminal to navigate the server.

<img src="https://i.imgur.com/CFBZeSs.png" height="70%" width="70%" alt="VirtualBox downloads"/>

After selecting the operating system, select Custom in order to install the operating system. 

<img src="https://i.imgur.com/XLL5Q8O.png" height="70%" width="70%" alt="VirtualBox downloads"/>

Click next to install the operating system to our hard drive. Then Windows will begin installing!

<img src="https://i.imgur.com/LZ5G8qQ.png" height="70%" width="70%" alt="VirtualBox downloads"/>

<img src="https://i.imgur.com/U4FhbKM.png" height="70%" width="70%" alt="VirtualBox downloads"/>



