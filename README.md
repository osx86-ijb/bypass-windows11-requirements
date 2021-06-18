## *The steps necessary to remove the "Secure Boot" and "TPM 2.0" requirements error when attempting to install Windows 11 Consumer Preview*

- *1)* Obtain a Windows 10 ISO
- *2)* Mount it 
- *3)* Find and locate the folder named Sources on the mounted ISO
- *4)* Copy all of the files in the Sources folder of the mounted ISO except install.wim / install.esd to the "Sources" folder of the bootable Windows 11 ISO USB          drive.
- *5)* Navigate to the Windows 11 bootable USB Installer that you've previously created in your File Manager
- *6)* Open the Sources folder on the Windows 11 bootable USB Installer
- *7)* Paste the previously copied contents/files from the "Sources" folder on the mounted Win 10 ISO to the Sources folder of the 
       Windows 11 bootable USB Installer, and make sure to replace the files present in the Windows 11 USB Installer Sources folder.
- *8)* Boot from Windows 11 USB Installer
- *9)* Profit from not having the requirements of Secure Boot and TPM 2.0 being enabled in place.

## _*(PS: You're welcome)*_
