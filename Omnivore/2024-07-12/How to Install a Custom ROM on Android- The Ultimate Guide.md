---
id: e7e9b86e-7941-4466-b460-d36d624cbd76
---

# How to Install a Custom ROM on Android: The Ultimate Guide
#Omnivore

[Read on Omnivore](https://omnivore.app/me/how-to-install-a-custom-rom-on-android-the-ultimate-guide-190a6a5b205)
[Read Original](https://www.wikihow.com/Install-a-Custom-ROM-on-Android)

[ ![PDF download](https://proxy-prod.omnivore-image-cache.app/150x150,s7Pkt8VWrprIbXCfM7fFrNB1MMYIu_DYBEpfguhkalXQ/https://www.wikihow.com/extensions/wikihow/socialstamp/images/icon-pdf.svg) Download Article ](#)

A comprehensive guide to custom Android ROMs 

[ ![PDF download](https://proxy-prod.omnivore-image-cache.app/150x150,s7Pkt8VWrprIbXCfM7fFrNB1MMYIu_DYBEpfguhkalXQ/https://www.wikihow.com/extensions/wikihow/socialstamp/images/icon-pdf.svg) Download Article ](#)

* [Before You Begin](#Before-You-Begin)
|
* [Enabling USB Debugging](#Enabling-USB-Debugging)
|
* [Installing Platform Tools](#Installing-Platform-Tools)
|
* [Unlocking the Bootloader](#Unlocking-the-Bootloader)
|
* [Installing a Custom Recovery](#Installing-a-Custom-Recovery)
|
* [Creating a Backup](#Creating-a-Backup)
|
* [Finding a ROM](#Finding-a-ROM)
|
* [Download GApps](#Download-GApps)
|
* [Installing the ROM](#Installing-the-ROM)
|
* [Video](#Video)
|
* [Q&A](#qa%5Fheadline)
|
* [Tips](#tips)
|
* [Warnings](#warnings)

A custom ROM changes the way the Android looks and operates, breathing new life into your old phone or tablet. Installing a custom ROM is an advanced procedure, and you risk rendering your Android device inoperable and voiding your warranty.

## Using a Custom Android ROM 

* Begin by enabling USB debugging on your Android.
* Install a custom recovery like TWRP on your Android using Fastboot ABD, then copy the ROM and Gapps into the root directory.
* Boot your phone into recovery mode, use TWRP to back up your device, and install the ROM and Gapps.

1. [![Step 1 Check if your manufacturer allows unlocking the bootloader.](https://proxy-prod.omnivore-image-cache.app/0x0,s_WyXRJxHuLWNNXcdMf4WUDHjsRiKnC51XBz3hqQzWuQ/https://www.wikihow.com/images/thumb/e/ea/Install-a-Custom-ROM-on-Android-Step-1-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-1-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-1-Version-5.jpg)  
 Depending on your Android model, you may be able to unlock the bootloader with the manufacturer's help. Not all manufacturers allow this; even if they do, not all models may be supported.  
   * To see which models your manufacturer allows to be unlocked, search "\[manufacturer's name\] unlock bootloader" (e.g., "HTC unlock bootloader"). This will typically display the manufacturer's bootloader website as the first result.
2. [![Step 2 Check if your carrier allows unlocking the bootloader.](https://proxy-prod.omnivore-image-cache.app/0x0,s0hBUcu_fRx23-UnclD0JHz5cNKor9PZVtolJt-Op4v4/https://www.wikihow.com/images/thumb/b/b7/Install-a-Custom-ROM-on-Android-Step-2-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-2-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-2-Version-5.jpg)  
 Even if the device manufacturer allows unlocking the bootloader, your carrier may not allow it. Contact your cellular provider's customer service and ask if they allow you to unlock the bootloader.  
Advertisement
3. [![Step 3 Understand the risks and limitations.](https://proxy-prod.omnivore-image-cache.app/0x0,s9lmeqZzi3n0ZRewxjiy1bgbAJIu8BpooRowlnrUdBto/https://www.wikihow.com/images/thumb/3/3d/Install-a-Custom-ROM-on-Android-Step-3-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-3-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-3-Version-5.jpg)  
 Several risks are involved with unlocking your bootloader and installing a custom ROM:  
   * **Void your warranty:** Unlocking the bootloader voids any warranty on your device, and you will lose support from the manufacturer.  
   * **Hardware and software issues:** Certain features may not work properly or may not work as well, and some apps may not be able to run.  
   * **Security risks:** Many custom ROMs do not allow the same level of encryption that the manufacturer's ROM allows. Installing custom ROMs may make you more susceptible to malware, viruses, and security breaches.[\[1\]](#%5Fnote-1)  
   * **Data loss:** During installation, you may lose the data on your phone. Be sure to [back up all data you want to keep](https://www.wikihow.com/Back-Up-Data "Back Up Data") before proceeding.  
   * **You may brick your phone:** In the worst-case scenario, installing a custom ROM may cause permanent damage to your phone and render it inoperable and unable to boot up.

Advertisement

1. [![Step 1 Open your Android's Settings.](https://proxy-prod.omnivore-image-cache.app/0x0,stscoMu6WiPiLrm0WhvMbcD38aE0jnflRopnp4Tah0HY/https://www.wikihow.com/images/thumb/9/97/Install-a-Custom-ROM-on-Android-Step-15-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-15-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-15-Version-4.jpg)  
 To do so, swipe down from the top of the screen and tap the gear icon in the upper-right corner.
2. [![Step 2 Scroll to the bottom and tap About phone.](https://proxy-prod.omnivore-image-cache.app/0x0,sqGpKy9EUMtNJjX-ecGOXmIxuf2f-OXZgA8-nSrjU16o/https://www.wikihow.com/images/thumb/0/05/Install-a-Custom-ROM-on-Android-Step-16-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-16-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-16-Version-4.jpg)  
 It's usually near the bottom of the Settings menu.
3. [![Step 3 Tap the Build Number entry seven times.](https://proxy-prod.omnivore-image-cache.app/0x0,szLl0rZz2twtXQdLj19k0alC-7OyHaY5yXlGIezcoBpc/https://www.wikihow.com/images/thumb/d/d2/Install-a-Custom-ROM-on-Android-Step-17-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-17-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-17-Version-4.jpg)  
 This will enable the Developer Options menu.  
   * "Build number" may be under "Software Information" on some phone models.
4. [![Step 4 Return to Settings and tap Developer Options.](https://proxy-prod.omnivore-image-cache.app/0x0,syOPClVoTI3svlcMCoq9xnEVekRpil2nx088zRIcVKQc/https://www.wikihow.com/images/thumb/1/1b/Install-a-Custom-ROM-on-Android-Step-18-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-18-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-18-Version-3.jpg)  
 Press the back arrow to return to the previous menu and tap the newly created "Developer Options" menu.
5. [![Step 5 Enable OEM unlocking (if present).](https://proxy-prod.omnivore-image-cache.app/0x0,shHIeyn7-Dogy1NhWcIIfdFoNHia7gdwllPaI5re1QLI/https://www.wikihow.com/images/thumb/7/70/Install-a-Custom-ROM-on-Android-Step-19-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-19-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-19-Version-3.jpg)  
 Not all phones will display this option, and it is only necessary if it is there.
6. [![Step 6 Enable USB debugging.](https://proxy-prod.omnivore-image-cache.app/0x0,sdsuy9zolNOMHTrk2cNpQxXCnk5A18ydOfK7ra-Vvqio/https://www.wikihow.com/images/thumb/4/45/Install-a-Custom-ROM-on-Android-Step-20-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-20-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-20-Version-3.jpg)  
 This allows you to send commands to your Android through ADB.

Advertisement

1. [![Step 1 Download the Android SDK tools you'll need.](https://proxy-prod.omnivore-image-cache.app/0x0,sqnKWO_AdrK2j4gt3qXeLokuDENDnfvjZuqniDQk_Q1U/https://www.wikihow.com/images/thumb/9/9b/Install-a-Custom-ROM-on-Android-Step-4-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-4-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-4-Version-4.jpg)  
 You'll need a few utilities on your computer to unlock your bootloader.  
   * Visit the \[hhttps://developer.android.com/tools/releases/platform-tools Android developer website\].  
   * Scroll down and click the download for your operating system.  
   * Scroll down and click the checkbox to agree to the terms of service.  
   * Click **Download Android SDK Platform Tools**.
2. [![Step 2 Extract the ZIP file.](https://proxy-prod.omnivore-image-cache.app/0x0,sh8kyGjLbmsZPg-rkx-Yis4IAS-3iu6HTDTy6Jjo_Hk4/https://www.wikihow.com/images/thumb/7/79/Install-a-Custom-ROM-on-Android-Step-5-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-5-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-5-Version-3.jpg)  
 Double-click the ZIP file after you've placed it in its folder and click the "Extract" option to [extract the contents of the ZIP file](https://www.wikihow.com/Open-a-Zip-File "Open a Zip File"). There should be a folder called "cmdline-tools" in the zip file. Place that folder in any location on your hard drive.
3. [![Step 3 Download and install the USB drivers for your Android model.](https://proxy-prod.omnivore-image-cache.app/0x0,sJ0Mr_bkLtL22yqc21FehLwoqX6pr-heTV1yfqfbEks8/https://www.wikihow.com/images/thumb/1/16/Install-a-Custom-ROM-on-Android-Step-9-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-9-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-9-Version-4.jpg)  
 You can find these on your device's manufacturer's support page.
4. [![Step 4 Connect your Android to your computer via USB.](https://proxy-prod.omnivore-image-cache.app/0x0,sFRDKYsrEeM_r9cA75OVXV8iONxt9bvGtrkcAEZPtv5Y/https://www.wikihow.com/images/thumb/9/96/Install-a-Custom-ROM-on-Android-Step-13-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-13-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-13-Version-5.jpg)  
 You can use the charger that came with your phone and connect it to a free USB port on your computer.
5. [![Step 5 Open the "Platform-tools" folder.](https://proxy-prod.omnivore-image-cache.app/0x0,sbq8XqQnzfAgwkU5X8oJnlHNLoRo_evaaWrA6SKw2riQ/https://www.wikihow.com/images/thumb/0/05/Install-a-Custom-ROM-on-Android-Step-14-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-14-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-14-Version-5.jpg)  
 It's inside the folder that was created when you extracted the zip file you downloaded.
6. [![Step 6 Open a command-line window.](https://proxy-prod.omnivore-image-cache.app/0x0,sgP1y_b1TwBgpzJDac_vlkRIwvkvPI00EnAK144qjc1Q/https://www.wikihow.com/images/thumb/4/4b/Install-a-Custom-ROM-on-Android-Step-15-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-15-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-15-Version-5.jpg)  
 To do so, click the address bar at the top, type "cmd", and press **Enter**.
7. [![Step 7 Type adb devices and press ↵ Enter.](https://proxy-prod.omnivore-image-cache.app/0x0,sjyZmgQhI--lM_RM2EnmZJViTxrqEWe-A51jDlc7GDsQ/https://www.wikihow.com/images/thumb/2/2c/Install-a-Custom-ROM-on-Android-Step-14-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-14-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-14-Version-4.jpg)  
 You should see your device's serial number.

Advertisement

1. [![Step 1 Connect your Android to your computer via USB.](https://proxy-prod.omnivore-image-cache.app/0x0,sox-qwB_H24LIqyMeWYUYnn7f8ljDGho1K21qzDoApPg/https://www.wikihow.com/images/thumb/1/1e/Install-a-Custom-ROM-on-Android-Step-17-Version-5.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-17-Version-5.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-17-Version-5.jpg)  
 You can use the charger that came with your phone and connect it to a free USB port on your computer.
2. [![Step 2 Open your device manufacturer's unlock code procedure instructions.](https://proxy-prod.omnivore-image-cache.app/0x0,sPLdYohIMCQnN8m34kRd97PjNO7-92kl2DlhSy1BxZ1Q/https://www.wikihow.com/images/thumb/6/60/Install-a-Custom-ROM-on-Android-Step-21-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-21-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-21-Version-3.jpg)  
 The following process will vary depending on your phone manufacturer. Be sure to follow the instructions they provide exactly. What follows here is a general guide.
3. [![Step 3 Reboot your device into the fastboot menu.](https://proxy-prod.omnivore-image-cache.app/0x0,sf_DAu_ExYK3pYjwH6zUus5eSQb8Xzgmfx8fmn8miIC0/https://www.wikihow.com/images/thumb/c/cb/Install-a-Custom-ROM-on-Android-Step-19-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-19-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-19-Version-4.jpg)  
 The process for this will vary depending on your device, but generally, you'll need to turn off your phone and then hold Power and Volume Down for 10 seconds.
4. [![Step 4 Type the unlock key retrieval command in the command line.](https://proxy-prod.omnivore-image-cache.app/0x0,scVDQJEfffGctSEpoULukboOv5vxfFvYFZ73gjHXDpI8/https://www.wikihow.com/images/thumb/6/68/Install-a-Custom-ROM-on-Android-Step-23-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-23-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-23-Version-3.jpg)  
 This command is different for every manufacturer. For example, for HTC, you would type fastboot oem get\_identifier\_token.  
   * Make sure your Android device is still connected to your computer and that the Command Prompt window is open from the platform-tools folder.
5. [![Step 5 Copy the device ID code.](https://proxy-prod.omnivore-image-cache.app/0x0,sXpPEKv3CjEtqNaYnDQzihbMu2caSCON-lAF5RqOBPig/https://www.wikihow.com/images/thumb/0/0e/Install-a-Custom-ROM-on-Android-Step-24-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-24-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-24-Version-3.jpg)  
 You'll see a long code appear on the screen, which may be broken into several lines. Copy the entire code.
6. [![Step 6 Submit your device ID code to the manufacturer.](https://proxy-prod.omnivore-image-cache.app/0x0,sVtiCFf9tZOvQWz9w7SpzDCCQslTtppCJy2We5Wy1AZs/https://www.wikihow.com/images/thumb/c/c9/Install-a-Custom-ROM-on-Android-Step-25-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-25-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-25-Version-3.jpg)  
 Use the bootloader unlock code request form to submit and request your unlock code. This can take a week or two, depending on the manufacturer.
7. [![Step 7 Run the command specified by your manufacturer.](https://proxy-prod.omnivore-image-cache.app/0x0,slW6DkgijwiuJzME4AYSDzkV9VlpFidpzkqghR6QhWTY/https://www.wikihow.com/images/thumb/d/db/Install-a-Custom-ROM-on-Android-Step-26-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-26-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-26-Version-3.jpg)  
 When you receive your unlock code, you'll be given the command to apply it to your device. This command varies depending on the manufacturer. Your Android must be connected to your computer and in fastboot mode.  
   * For Nexus devices, run fastboot oem unlock, or fastboot flashing unlock for the Nexus 5X and newer.  
   * The command for your manufacturer may be different. For example, HTC users would type fastboot oem unlocktoken Unlock\_code.bin after placing the Unlock\_code.bin file received from HTC into the ADB folder.
8. [![Step 8 Confirm that you want to unlock.](https://proxy-prod.omnivore-image-cache.app/0x0,s1GxQPNjS8ujWXibXbo2kY7jwo7d0Nmr_-0D8sQHcGl8/https://www.wikihow.com/images/thumb/1/1e/Install-a-Custom-ROM-on-Android-Step-24-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-24-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-24-Version-4.jpg)  
 You may be prompted by your phone to confirm the unlock.
9. [![Step 9 Type fastboot reboot on your computer.](https://proxy-prod.omnivore-image-cache.app/0x0,spfcD-9Fyq6mY90rNB64BKOeqfzToNI_9LM4xbI3vLg4/https://www.wikihow.com/images/thumb/0/01/Install-a-Custom-ROM-on-Android-Step-28-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-28-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-28-Version-3.jpg)  
 This command will reboot your device and exit fastboot mode.
10. [![Step 10 Look for the Bootloader Unlocked message.](https://proxy-prod.omnivore-image-cache.app/0x0,sctkKMHZKAby52ftm6CWh7RYUG6Dn6KDL-LzV8n4XK_k/https://www.wikihow.com/images/thumb/e/e9/Install-a-Custom-ROM-on-Android-Step-26-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-26-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-26-Version-4.jpg)  
 You'll see this message every time you turn on your device as a security measure. Make sure your device boots completely into the Android operating system as normal. You're now ready to install a custom recovery.
11. [![Step 11 Find and follow a device-specific guide if you can't unlock the bootloader.](https://proxy-prod.omnivore-image-cache.app/0x0,sbeg608defjmfqrdZI6RgypIrfdx2dRyFSjZdcgVGu8c/https://www.wikihow.com/images/thumb/3/3b/Install-a-Custom-ROM-on-Android-Step-27-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-27-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-27-Version-4.jpg)  
 If your manufacturer or carrier will not allow you to unlock the bootloader, your only other option is to find and use an exploit to bypass it. This process is different for _every_ phone model, and some phones cannot be unlocked at all.  
   * The best place to start is the [XDA Forums](https://forum.xda-developers.com/). Find your phone model and look for any bootloader unlocks released by the community.  
   * When performing an unlock using an exploit, follow every step in the XDA thread _exactly,_ as the risk of bricking your device increases dramatically when not using official methods.

Advertisement

1. [![Step 1 Visit the TWRP...](https://proxy-prod.omnivore-image-cache.app/0x0,srMMivIpRZEO0rIxxGFVSisXajk_LxEVXI-v9YFYUj04/https://www.wikihow.com/images/thumb/8/82/Install-a-Custom-ROM-on-Android-Step-31-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-31-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-31-Version-3.jpg)  
**Visit the [TWRP website](https://twrp.me/).** This guide will cover installing TeamWinRecoveryProject (TWRP), one of the more popular recovery methods for Android ROMs. [\[2\]](#%5Fnote-2)  
   * Another popular recovery is [ClockworkMod Recovery (CWM)](https://www.clockworkmod.com/). Both should work for installing most ROMs, though some will require a specific recovery environment.
2. [![Step 2 Click the Devices tab.](https://proxy-prod.omnivore-image-cache.app/0x0,stpiGSNEEvBfuc7fnkA1VzSbvj6qAEwG6CaH1NawVsk0/https://www.wikihow.com/images/thumb/d/d8/Install-a-Custom-ROM-on-Android-Step-32-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-32-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-32-Version-3.jpg)  
 It's in the upper-right corner of the web page.
3. [![Step 3 Verify that your device is supported.](https://proxy-prod.omnivore-image-cache.app/0x0,sYbAX30yBnKzq4HFoOE6ENrhzBB91e2O0e_E1EJwTnEc/https://www.wikihow.com/images/thumb/c/c1/Install-a-Custom-ROM-on-Android-Step-33-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-33-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-33-Version-3.jpg)  
 If your device is not on this list, try a different recovery environment like CWM.  
   * Note that while your device might be supported, your carrier or region may not.
4. [![Step 4 Click the link for your device.](https://proxy-prod.omnivore-image-cache.app/0x0,sF0BCM98itENow1UDSRlcz5xeBSPCT6FBiXuw9z-ylQI/https://www.wikihow.com/images/thumb/e/e7/Install-a-Custom-ROM-on-Android-Step-34-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-34-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-34-Version-3.jpg)  
 This will display more details for your specific device.
5. [![Step 5 Click the Download link.](https://proxy-prod.omnivore-image-cache.app/0x0,sdNfQUMQcPH2Mwqrx8XjlQX32f9rco5D6ZhoiIQl0JyA/https://www.wikihow.com/images/thumb/7/79/Install-a-Custom-ROM-on-Android-Step-35-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-35-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-35-Version-3.jpg)  
 This will download TWRP in IMG format to your computer.
6. [![Step 6 Copy the IMG file to your ADB folder.](https://proxy-prod.omnivore-image-cache.app/0x0,sy1RrluGy9WdXZQrq2l3VgVpP3dQmM9C33aRhXZEQHXA/https://www.wikihow.com/images/thumb/1/19/Install-a-Custom-ROM-on-Android-Step-36-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-36-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-36-Version-3.jpg)  
 Place it in the same location as your ADB binary files. This will allow you to transfer it to your phone using ADB in the Command Prompt.
7. [![Step 7 Rename the file to twrp.img.](https://proxy-prod.omnivore-image-cache.app/0x0,sa5rA56rYzLur6Toql6pmUF8BZwEEkYXFcokQWyzwgjI/https://www.wikihow.com/images/thumb/1/1d/Install-a-Custom-ROM-on-Android-Step-37-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-37-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-37-Version-3.jpg)  
 This will make it easy to enter the name during the transfer.
8. [![Step 8 Type adb reboot bootloader in the Command Prompt.](https://proxy-prod.omnivore-image-cache.app/0x0,s9MTJ98DmJofQET0-AMA6bUfrQxlz_S-gCCe96BhiAeQ/https://www.wikihow.com/images/thumb/5/51/Install-a-Custom-ROM-on-Android-Step-38-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-38-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-38-Version-3.jpg)  
 If you don't still have the Command Prompt open, hold **Shift** and right-click in the open platform-tools folder. Select "Open command window here."
9. [![Step 9 Type fastboot flash recovery twrp.img and press ↵ Enter.](https://proxy-prod.omnivore-image-cache.app/0x0,sQ12a_g2IkZ1i3Mh_y3rKcpXiTtgj7UBiCqPnA0pqw4o/https://www.wikihow.com/images/thumb/a/a4/Install-a-Custom-ROM-on-Android-Step-39-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-39-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-39-Version-3.jpg)  
 This will copy the TWRP image file to your Android device and replace your current recovery environment with it.
10. [![Step 10 Type fastboot reboot and press ↵ Enter.](https://proxy-prod.omnivore-image-cache.app/0x0,s1EPN5JX34dHZs1dyEXDro7ZHNYs6KDqJN4gyBlatpUs/https://www.wikihow.com/images/thumb/3/36/Install-a-Custom-ROM-on-Android-Step-40-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-40-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-40-Version-3.jpg)  
 This will reboot your Android device.

Advertisement

1. [![Step 1 Press and hold the Volume Up and Power buttons as the device reboots.](https://proxy-prod.omnivore-image-cache.app/0x0,s0NlAWK6C9YL2jSW0y4hf38Tg9gay6d031b7c-0TCPic/https://www.wikihow.com/images/thumb/1/13/Install-a-Custom-ROM-on-Android-Step-38-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-38-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-38-Version-4.jpg)  
 This will enter recovery mode in most devices.  
   * Some devices may have a different button combination for entering recovery mode. Perform a web search for "_model_ recovery mode."
2. [![Step 2 Enter your PIN if prompted.](https://proxy-prod.omnivore-image-cache.app/0x0,s0PRy2GD0WKJiF9fTGN6g3V9wkxySkVkyLBhnRQUSgA8/https://www.wikihow.com/images/thumb/9/9c/Install-a-Custom-ROM-on-Android-Step-39-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-39-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-39-Version-4.jpg)  
 This will allow TWRP to access your encrypted device, which is essential for creating backups.
3. [![Step 3 Back up your data.](https://proxy-prod.omnivore-image-cache.app/0x0,sCThrv_51ZP2dCQtc8Y8DYCqXsm4lx3RrRSA4KR1IfnY/https://www.wikihow.com/images/thumb/9/95/Install-a-Custom-ROM-on-Android-Step-40-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-40-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-40-Version-4.jpg)  
 This will create a full system backup, allowing you to restore your device if something goes wrong. Use the following steps to create a backup:  
   * Tap **Backup**.  
   * Tap **Boot**.  
   * Tap **System**.  
   * Tap **Data'**.  
   * Swipe the bar to begin the backup.
4. [![Step 4 Return to the Backup menu and clear all of the options.](https://proxy-prod.omnivore-image-cache.app/0x0,sEtKsA7NBSbXX_3Nr2F-1UemH7hMC8rt-KfjexEGZfgI/https://www.wikihow.com/images/thumb/3/32/Install-a-Custom-ROM-on-Android-Step-46-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-46-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-46-Version-3.jpg)  
 Tap the back arrow until you return to the Backup menu.
5. [![Step 5 Scroll to the bottom and select your special partition after Recovery.](https://proxy-prod.omnivore-image-cache.app/0x0,saiVL7J5eEXCySa1qe9cJgL2HpOHkYj9Cp9spzl3MIjA/https://www.wikihow.com/images/thumb/3/3c/Install-a-Custom-ROM-on-Android-Step-47-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-47-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-47-Version-3.jpg)  
 This will have different names depending on your device (PDS, EFS, WiMAX, etc.), and your device may not have anything listed here.
6. [![Step 6 Start another backup with your special partition selected.](https://proxy-prod.omnivore-image-cache.app/0x0,svJfYyUG8tge3nhmYJJF_N18c_gDEjZoIFuwo8bswEKI/https://www.wikihow.com/images/thumb/7/76/Install-a-Custom-ROM-on-Android-Step-48-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-48-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-48-Version-3.jpg)  
 This will back up your IMEI information, which will be essential for restoring connectivity if you break something later.

Advertisement

1. [![Step 1 Visit the XDA...](https://proxy-prod.omnivore-image-cache.app/0x0,stFUkp0YyiyRK6X5dWxzEr42DsBBoJowLJG2GN9HB2yk/https://www.wikihow.com/images/thumb/d/dd/Install-a-Custom-ROM-on-Android-Step-49-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-49-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-49-Version-3.jpg)  
**Visit the [XDA forums](https://forum.xda-developers.com/).** The XDA forums are the most popular Android development community on the internet, and you'll find virtually every available ROM here.
2. [![Step 2 Open the subforum for your device.](https://proxy-prod.omnivore-image-cache.app/0x0,sNnCRipEdb8f9nl8CuVEo33KaEWU-6vZD3k3n-ZgmUls/https://www.wikihow.com/images/thumb/2/25/Install-a-Custom-ROM-on-Android-Step-50-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-50-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-50-Version-3.jpg)  
 You'll see popular devices listed on the main page, or you can use the search bar to find your specific model.  
   * Make sure your model matches both your device and your carrier. The same device on two carriers will have two different model numbers, and you'll need a ROM matching your exact model.
3. [![Step 3 Click the Development tab.](https://proxy-prod.omnivore-image-cache.app/0x0,sW6FTxg6HV_F-FspC-SvrwBIJr88oOFoKPJ9ZA8dXuIw/https://www.wikihow.com/images/thumb/d/db/Install-a-Custom-ROM-on-Android-Step-46-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-46-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-46-Version-4.jpg)  
 It's at the top of the page. This filters development forums.
4. [![Step 4 Find a ROM that looks interesting.](https://proxy-prod.omnivore-image-cache.app/0x0,st5kKTjXfW1gTt0Q8N2GotZiSavlyYtxFTtbj91pS8YE/https://www.wikihow.com/images/thumb/1/10/Install-a-Custom-ROM-on-Android-Step-52-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-52-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-52-Version-3.jpg)  
 Threads that have a ROM for download will generally say "\[ROM\]" in the thread title. The number of ROMs available for your device heavily depends on its popularity. Some devices may only have one or two ROMs to choose from, while others may have dozens. Some devices don't have any ROMs available, but these are usually devices that don't have unlockable bootloaders.  
   * Different ROMs can accomplish different things. Some ROMs are designed to be as barebones as possible for maximum performance, while others will add a bunch of features that aren't normally available on your device.
5. [![Step 5 Look for features and limitations.](https://proxy-prod.omnivore-image-cache.app/0x0,sin9qT6BHvX88m5pR6lwlJdF937s7rlhKmq79aUZYPOA/https://www.wikihow.com/images/thumb/f/f3/Install-a-Custom-ROM-on-Android-Step-53-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-53-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-53-Version-3.jpg)  
 ROMs often add new features but also have limitations that may not have been present on your original device. Make sure that you will be OK with the feature set of your new ROM.
6. [![Step 6 Carefully read the entire post for the ROM.](https://proxy-prod.omnivore-image-cache.app/0x0,sj4qxkjy5fDI4ukS_9I4T81qSqhPgGsZGkvzbPOikv9c/https://www.wikihow.com/images/thumb/7/7a/Install-a-Custom-ROM-on-Android-Step-54-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-54-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-54-Version-3.jpg)  
 Many ROMs will have special instructions you must follow during installation. It is imperative that you follow the author's instructions _exactly_, or you may encounter serious problems.
7. [![Step 7 Click the Download link for the ROM file.](https://proxy-prod.omnivore-image-cache.app/0x0,scJ18MSG2ILVYFP2m0LvOMgC58SyqQdYUcJ2sSpQlAhc/https://www.wikihow.com/images/thumb/1/1b/Install-a-Custom-ROM-on-Android-Step-55-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-55-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-55-Version-3.jpg)  
 This will begin downloading the ROM file, usually in ZIP form. ROMs may be large, and the file could take a while to download.

Advertisement

1. [![Step 1 Visit the GApps...](https://proxy-prod.omnivore-image-cache.app/0x0,sITncaOWFprqNSXEgx65-NuWU1RJI00s2XI9NldrIpUA/https://www.wikihow.com/images/thumb/a/a2/Install-a-Custom-ROM-on-Android-Step-56-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-56-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-56-Version-3.jpg)  
**Visit the [GApps download site](http://opengapps.org/).** This site lets you download Googe's proprietary apps like Gmail and the Play Store since ROMs cannot legally include them.
2. [![Step 2 Select your device's configuration on the GApps site.](https://proxy-prod.omnivore-image-cache.app/0x0,saIf8b5EtdC0xXbuN2OZmVIhp9GAP00o0RSYK2rLE5-c/https://www.wikihow.com/images/thumb/f/fb/Install-a-Custom-ROM-on-Android-Step-57-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-57-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-57-Version-3.jpg)  
 You'll need to select your device's architecture (platform), operating system version, and the variant you want.  
   * If you don't know your device's platform, you should be able to find it on the XDA Forum's device information page for your device.  
   * Make sure the OS version matches the ROM you are installing, not your current version.  
   * Most users can select Stock as the variant, including all the default GApps.
3. [![Step 3 Click the Download button.](https://proxy-prod.omnivore-image-cache.app/0x0,sLzAkvoFJ1rbj5m7PPjlJIWNIrIlOwkOMYx5epcz6kSk/https://www.wikihow.com/images/thumb/1/18/Install-a-Custom-ROM-on-Android-Step-58-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-58-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-58-Version-3.jpg)  
 This will begin downloading your selected GApps package. You should now have two ZIP files: your chosen ROM and the GApps file.

Advertisement

1. [![Step 1 Connect your Android to your computer.](https://proxy-prod.omnivore-image-cache.app/0x0,swcf11oO_mz3Bf45Ob3MECPuaMi19Tv5Obk2t7HMXtqI/https://www.wikihow.com/images/thumb/2/21/Install-a-Custom-ROM-on-Android-Step-54-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-54-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-54-Version-4.jpg)  
 If it isn't already, you'll need to connect your Android to your computer via USB to transfer the files onto the device's storage.
2. [![Step 2 Open your Android's storage on your computer.](https://proxy-prod.omnivore-image-cache.app/0x0,sckSnVyUcIeE4hrbvQZmssXOToM-CePyU31k8UR1QWx8/https://www.wikihow.com/images/thumb/3/38/Install-a-Custom-ROM-on-Android-Step-60-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-60-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-60-Version-3.jpg)  
 You can transfer the files to your Android's internal storage or the SD card if you have one inserted.
3. [![Step 3 Copy the ROM and GApps ZIP files onto your Android.](https://proxy-prod.omnivore-image-cache.app/0x0,sJqvTg3XnWiuqoE8UxC0MVbXkX8qIYF0e12PrZV7HIj4/https://www.wikihow.com/images/thumb/0/06/Install-a-Custom-ROM-on-Android-Step-61-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-61-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-61-Version-3.jpg)  
 You can click and drag them to your device's storage. Make sure they are placed in the base directory for either the internal storage or the SD card (don't put them in folders).
4. [![Step 4 Disconnect your phone after transferring.](https://proxy-prod.omnivore-image-cache.app/0x0,seKoFikpAAIR0e3apc5sQvC_3QaLEQ6jAaBio8qkXTBg/https://www.wikihow.com/images/thumb/d/d5/Install-a-Custom-ROM-on-Android-Step-57-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-57-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-57-Version-4.jpg)  
 Disconnect the USB cord from your Android phone after the files finish transferring.
5. [![Step 5 Power off your Android device.](https://proxy-prod.omnivore-image-cache.app/0x0,s4LJ5OkPuHlnoXo9bg4WXcu5RdtGFrhUTb93CLbdXVjU/https://www.wikihow.com/images/thumb/9/94/Install-a-Custom-ROM-on-Android-Step-58-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-58-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-58-Version-4.jpg)  
 You'll need to open Recovery mode, which you'll do from the powered-off state.
6. [![Step 6 Boot your Android into recovery mode.](https://proxy-prod.omnivore-image-cache.app/0x0,sAFdkFcnJrZKf6U_PyvBk14nLARujAcGd_FU5ck_ilAk/https://www.wikihow.com/images/thumb/c/c3/Install-a-Custom-ROM-on-Android-Step-59-Version-4.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-59-Version-4.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-59-Version-4.jpg)  
 This process will vary depending on your device, so perform a web search if you aren't sure. Generally, you'll hold Power and Volume Down until the recovery menu appears. You'll know you're in the right place when you see TWRP.
7. [![Step 7 Tap Wipe.](https://proxy-prod.omnivore-image-cache.app/0x0,sj6mxExSJl249AgWje9-gjMh_A1Bew-caVW3Ma70xvgc/https://www.wikihow.com/images/thumb/8/86/Install-a-Custom-ROM-on-Android-Step-65-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-65-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-65-Version-3.jpg)  
 It is always recommended that you wipe your device before installing a new ROM. This will delete all of the data on the device.
8. [![Step 8 Swipe the bar to perform a factory reset.](https://proxy-prod.omnivore-image-cache.app/0x0,s8H97E8xmlodFde6w1H3fjXpPpstl8_NY1Rz8YMLhsIY/https://www.wikihow.com/images/thumb/7/7e/Install-a-Custom-ROM-on-Android-Step-66-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-66-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-66-Version-3.jpg)  
 The reset process will only take a few moments.
9. [![Step 9 Tap Install on the TWRP main menu.](https://proxy-prod.omnivore-image-cache.app/0x0,sPKlsIxutbPkWvbHKS8WuDUl5KV046aQDU8KPlrzXjxk/https://www.wikihow.com/images/thumb/e/e5/Install-a-Custom-ROM-on-Android-Step-67-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-67-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-67-Version-3.jpg)  
 It's in the upper right corner.
10. [![Step 10 Scroll down and tap the ZIP file for your ROM.](https://proxy-prod.omnivore-image-cache.app/0x0,sFux_IF_ZEQZdht9d5FpXN8vY-kEZRCCDyXVPu34EStk/https://www.wikihow.com/images/thumb/2/21/Install-a-Custom-ROM-on-Android-Step-68-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-68-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-68-Version-3.jpg)  
 Make sure to start with the ROM, not the GApps file.
11. [![Step 11 Swipe the bar to start flashing.](https://proxy-prod.omnivore-image-cache.app/0x0,stDlWrcYP11hEYoU5adGJwju-sxtS2Ok9zeDxN2Uti7o/https://www.wikihow.com/images/thumb/3/3c/Install-a-Custom-ROM-on-Android-Step-69-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-69-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-69-Version-3.jpg)  
 The ROM file will begin installing, which may take several minutes to complete.
12. [![Step 12 Return to the main menu after flashing and tap Install again.](https://proxy-prod.omnivore-image-cache.app/0x0,sgdPx0BmKxkfrmQXazJ4SbGiKJm-az8Rmc8ESDAplTDU/https://www.wikihow.com/images/thumb/0/04/Install-a-Custom-ROM-on-Android-Step-70-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-70-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-70-Version-3.jpg)  
 Now you'll be installing the GApps file
13. [![Step 13 Scroll down and tap the GApps ZIP file.](https://proxy-prod.omnivore-image-cache.app/0x0,sRyLq7gzg-Y44ee4GWVq5Agnn24R458PLVHoYHp21GTg/https://www.wikihow.com/images/thumb/3/3a/Install-a-Custom-ROM-on-Android-Step-71-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-71-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-71-Version-3.jpg)  
 It should be in the installation menu.
14. [![Step 14 Swipe the bar to begin the installation.](https://proxy-prod.omnivore-image-cache.app/0x0,siDD1q0ZkCo-MKmWaMsO-UwckPtSZu2LQIRCicAnMRQo/https://www.wikihow.com/images/thumb/d/d6/Install-a-Custom-ROM-on-Android-Step-72-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-72-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-72-Version-3.jpg)  
 The GApps installation will begin, which may take as long or longer than the ROM installation.
15. [![Step 15 Tap Wipe cache/dalvik and then swipe to confirm.](https://proxy-prod.omnivore-image-cache.app/0x0,sW-jOkVt2sTlH_widv74xMbAcvNz7RpPzG8FioXFZWKA/https://www.wikihow.com/images/thumb/1/10/Install-a-Custom-ROM-on-Android-Step-73-Version-3.jpg/v4-460px-Install-a-Custom-ROM-on-Android-Step-73-Version-3.jpg) ](#/Image:Install-a-Custom-ROM-on-Android-Step-73-Version-3.jpg)  
 This will clear the cache, which is necessary for starting the ROM the first time.
16. Your Android device will reboot, and if everything went smoothly, you'll load your ROM's home screen environment.  
   * It may take a long time for your new ROM to boot. This should only happen the first time you boot it up.

Advertisement

Add New Question

* Question  
I have a Huawei Ascend Y250\. When I try to install Lollipop ROM, it shows an error, then aborts. What am I doing wrong?  
 This can occur if your phone is not rooted. You can use Kingroot or other root apps.
* Question  
What if I have already downloaded the ROM?  
Akash Sawarkar  
Community Answer  
 Switch off your phone and reboot it into recovery mode by pressing 'vol+' or 'vol-' and power button at the same time. If the Android logo appears on the screen, leave the buttons and you will see you are in recovery mode. In recovery mode, click on update from SD card / storage and select the downloaded ROM from your storage. It will start flashing the file and the device will be updated.
* Question  
I'm about to buy AsusROG phone 2 and I want a custom ROM. But I am scared if my armory crate (a specific app on rog phones) will be deleted.  
 Armory crate will be removed if you install a custom rom. But you can just download the app from the play store again, so don't worry.

[See more answers](https://www.wikihow.com/Questions/Install-a-Custom-ROM-on-Android#offset=3) 

Ask a Question

200 characters left

Include your email address to get a message when this question is answered.

Submit 

Advertisement

## Video 

* There are device-specific methods that are significantly different than the steps outlined above. Read all instructions for unlocking your device's bootloader and flashing a ROM.

 Thanks for submitting a tip for review!

Advertisement

* Performing a step incorrectly or out of order can permanently brick your device. Always read all of your device-specific instructions carefully before proceeding.

Advertisement

## References 

## About This Article

Thanks to all authors for creating a page that has been read 249,356 times.

## Is this article up to date?
  
  
Keep up with tech in just 5 minutes a week!

[Subscribe](#)

You're all set!

[X](#)

For over a decade, we’ve been on a mission: to help everyone in the world learn how to do anything. Today, we’re asking that you join us. Any amount that you can contribute helps us to continue providing readers like you with trusted, accurate and up-to-date information. **Please consider supporting our continued work with a contribution to wikiHow.**

\-

