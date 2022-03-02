# DISCLAIMER:

## THIS INFORMATION IS DONE PURELY AS RESEARCH, AND IS IN NO MAY MEANT TO PROMOTE CIRCUMVENTING ANYTHING THAT IS SOMEONE ELSE'S CORPORATE PRIVATE PROPERTY. THE INFORMATION LISTED HERE IS PURELY FOR EDUCATIONAL PURPOSES. SHOULD YOU CHOOSE TO UTILIZE IT IN ANY WAY, I AM IN NO WAY RESPONSIBLE FOR ANY INJUNCTIONS/PROBLEMS THAT MAY OR MAY NOT BE ARISE/BE BROUGHT AGAINST ANOTHER FOR THEIR CHOOSING TO HAVE DONE SO.

### *There are three different methods and ways that you can use to steps to remove the "Secure Boot" and "TPM 2.0" requirements error when attempting to install Windows 11 Consumer Preview (for now, some methods might not work in the future though depending on whether or not Microsoft wants to patch such!) on machines that do not meet either of those requirements. The methods listed are listed below, and as follows*:

### Method 1:

- *1)*  Obtain the newest available Windows 10 ISO.
- *2)*  Obtain the Windows 11 image.
- *3)*  Make your Windows 11 USB Installer using Rufus.
- *4)*  Mount Windows 10 ISO.
- *5)*  Find and locate the folder named Sources on the downloaded and mounted Windows 10 ISO.
- *6)*  Copy all of the files in the Sources folder of the mounted ISO *except for* install.wim / install.esd.
- *7)*  Navigate to the Windows 11 bootable USB Installer that you've previously created in your File Manager.
- *8)*  Open the Sources folder on the Windows 11 bootable USB Installer.
- *9)*  Paste the previously copied contents/files from the Sources folder on the mounted Win 10 ISO to the Sources folder of the 
        Windows 11 bootable USB Installer, and make sure to replace the files present in the Windows 11 USB Installer Sources folder.
- *10)*  Boot from Windows 11 USB Installer.
- *11)*  Profit.

### Method 2:

- *1)*  Obtain the Windows 11 image.
- *2)*  Obtain the newest Windows 10 image using (https://uup.rg-adguard.net/), or MSDN.
- *3)*  Create a USB Installer with Rufus application (in Windows), using the Windows 10 image.
- *4)*  Mount the Windows 11 image.
- *5)*  Navigate to the "sources" folder on the mounted Windows 11 image.
- *6)*  Copy the file "install.wim" from said folder.
- *7)*  Open up the Windows 10 USB Installer that you've made in Windows Explorer / File Explorer.
- *8)*  Navigate to the "sources" folder on the Windows 10 Installer USB.
- *9)*  Paste the "install.wim" file that you copied from the "sources" folder on the mounted Windows 11 image to the "sources" folder of the Windows 10 installer USB.
- *10)*  Boot from the created Windows 10/11 (install.wim) USB Installer that you've just finished creating and editing.
- *11)*  Profit.

### Method 3:

- *1)*  Obtain Windows 11 image
- *2)*  Make Windows 11 USB Installer using Rufus on Windows
- *3)*  Boot machine from created Windows 11 USB Installer
- *4)*  Press "Shift Key + F10"
- *5)*  Open Registry Editor
- *6)*  Navigate to "HKEY_LOCAL_MACHINE\SYSTEM\Setup"
- *7)*  Create key "LabConfig"
- *8)*  Add "BypassTPMCheck"=dword:00000001
- *9)*  Add "BypassSecureBootCheck"=dword:00000001
- *10)*  Profit.

## _*(PS: You're welcome)*_

![Was it REALLY that hard, smart guys?](https://i.ibb.co/FhwBD9v/Mhm-copy.png)
