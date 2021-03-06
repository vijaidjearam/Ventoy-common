# Prepare bootable USB for custom windows Installation
  * Download the latest version of Ventoy from [here](https://github.com/ventoy/Ventoy/releases).
  * Unzip the downloaded ventoy file and launch Ventoy2Disk.exe.
  * Follow the onscreen instructions and prepare your usb-drive accordingly.
  * After installation copy the contents of this repository to the root of the usb-drive.
  * Download and place your .iso files in the *ISO* folder.
  * The name of the .iso file is very important and should correspond in the *ventoy.json* file in *ventoy* directory.
![image](https://user-images.githubusercontent.com/1507737/138076286-dd5f0d52-8603-4a28-8053-6601447ea7d8.png)
  * Thats it...:wink: 
  * To inject drivers to the windows, you can manually download the drivers and place it in the *drivers* folder.
 ![image](https://user-images.githubusercontent.com/1507737/139078177-02a1f6dd-95f5-46f6-9f28-8170f50db9f0.png)
  * To download drivers 

      1.Go to [www.dell.com/support](https://www.dell.com/support/home/fr-fr).

      2.Enter Dell Service Tag, Dell EMC Product ID, or Model.

      3.Click Drivers & Downloads.

      4.From the Operating system drop-down list, select the operating system.

      5.From the Category drop-down list, select **Systems Management**.

      6.Click **Dell Command Deploy Driver Pack** or Dell Command Deploy WinPE Driver Pack.

      7.Deploy Driver Pack contains the drivers in the form of .CAB files  -> extract the file using 7zip 

      8.You can also visit this [link](https://www.dell.com/support/kbdoc/en-us/000124139/dell-command-deploy-driver-packs-for-enterprise-client-os-deployment) to download Driver Pack

  * The powershell script that drives the customisation of windows is downloaded during windows install and launched during first logon.
![image](https://user-images.githubusercontent.com/1507737/138085973-55559b56-0248-4335-9516-e731e77567ed.png)
![image](https://user-images.githubusercontent.com/1507737/138086160-f1f29120-ff40-47fd-9789-25e718813627.png)
  * :imp: After windows installation, the custom script will update BIOS firmware and settings. So make sure the BIOS password is cleared before you start the process.
  * Boot from the Usb-drive,select the .iso and then the appropriate answerfile to install.


  
  


