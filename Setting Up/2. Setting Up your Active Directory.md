Here are the steps to setting up an Active Directory

# Downloading Windows Server Disc File

Download the "Windows Server 2019" Disc File (.iso) from this [site](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019) 

# Setting Up Virtual Box

Before we proceed, make sure your Virtual Box is installed. If you do not have it installed, do now by clicking on this link [download Virtual Box](https://www.virtualbox.org/wiki/Downloads). 

For this demo, we will be downloading it to our Windows PC.

# Configuring Virtual Box 

Now that our __Virtual Box__ application is installed, follow the steps below

### 1. Click "New"

### 2. Enter the "Name" you would like to give to your Active Directory 
<img src="https://github.com/user-attachments/assets/53df1623-cdf8-4e82-a689-71e9e895062f" width="600">

### 3. Select "Type" as "Microsoft Windows" 

### 4. Select "Version" as "Windows 2019" 

You may Skip the "Unattended Install".

### 5. Go to Hardware and select the desired settings

<img src="https://github.com/user-attachments/assets/c276091e-4f0b-4b34-bead-1c214e231fa2" width="600">

### 6. Go to the Hard Disk Setting

Make sure you have selected a sufficient size.

<img src="https://github.com/user-attachments/assets/b8cefb86-1f48-4f38-9e26-d22b9b316cc7" width="600">

Then Select "Done"

### 7. Now once the setup is complete, right-click on the "Machine" and click Settings 

### 8. Click "General" and go to "Description". 

Add your Admin username and password you want to enter. By the way, this is just for us, so we can remember it in the future.

Also for Password, choose a password that is present in the "Rock You" Wordlist. 
Some of the Password you can choose is:
- 1crissy
- 1crazymoma
- 1crazygurl

<img src="https://github.com/user-attachments/assets/6dd6e2ea-48ca-4db3-badd-fefe64cc2aac" height="600">

### 9. Go to "Storage" 

Select "Optical Device" and "Choose a Disk File" 

Select the ISO File you downloaded

<img src = "https://github.com/user-attachments/assets/41d8017d-661e-401b-9c3e-df8c25fae7c6" height="600">

### 10. Now go to "Network" and select "attach to" to "Bridged Adapter"

<img src = "https://github.com/user-attachments/assets/8f2ab417-f274-48d7-8c11-e635b6aab4b6" height="600">

### 11. in "Promisous Mode" select Allow All

<img src  = "https://github.com/user-attachments/assets/4200c932-78a0-4dee-89e9-e961ce438001" height="600">

### 12. We now click "OK" and then click on the green arrow to "Start"

