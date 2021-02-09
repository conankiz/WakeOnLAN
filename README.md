## WakeOnLAN
### Table of contents

[I. Introducton](#modau)

[II. Getting Start](#batdau)
- [Step 1: BIOS setting](#step1)
- [Step 2: Network adapter settings](#step2)
- [Step 3: Check the power option](#step3)
- [Step 4: Try Wake on Lan with WakeMeOnLan Soft](#step4)


[III. Summary](#Tongket)

===========================

<a name="Modau"></a>
## I. Introduction

<a name="batdau"></a>
## II. Getting Start:

<a name="step1"></a>
## Step 1:BIOS setting:
- 1: Power on the system.
- 2: When POST screen is displaying then press the keyboard "Del" key to enter to the BIOS setting.
- 3: Switch to Advanced page, select ACPI Configuration, change PCIE Devices Power On to Enabled.
<img src="https://i.imgur.com/23LmO6s.png">
- 4: Press "F10" key to save the BIOS setting and restart the system.

<a name="step2"></a>
## Step 2:Network adapter settings:
- 1: Start Windows and open Device Manager.
<img src="https://i.imgur.com/Wm7GDjQ.png">
- 2: Expand "Network adapter", right-click "Intel (R) I 211 Gigabit Network Connection", and click "Properties".
<img src="https://i.imgur.com/OIbyh4K.png">
- 3: Select the "Power Management" tab.
<img src="https://i.imgur.com/S3ZA041.png">
- 4: Please check "Enable computer to release standby state on this device".
- 5: Next, click the "Advanced Settings" tab, select the "Wake on Magic Packet" from the "Property" column, confirm that the "Value" is "Enabled" and click the "OK" button.
<img src="https://i.imgur.com/NFwkbvt.png">

<a name="step3"></a>
## Step 3: Check the power option:
- 1: Open the Power Option item in control panel.
<img src="https://i.imgur.com/8lZZvVU.png">
- 2: Click the Choose what the power buttons do link.
<img src="https://i.imgur.com/0hbvmnb.png">
- 3: Click Change settings that are currently unavailable.
<img src="https://i.imgur.com/zyGZTB5.png">
- 4: Clear the Turn on fast startup(recommend) check box.
<img src="https://i.imgur.com/22zu0T9.png">
- 5: Click Save changes.
After above setting, WOL function should work properly.

<a name="step4"></a>
## Step 4: Try Wake on Lan with WakeMeOnLan Soft:
- Download : https://www.nirsoft.net/utils/wake_on_lan.html
- Right click on PC want wake up -- select Wake up selected Computers (or F8)
<img src="https://i.imgur.com/EfOaYBa.png">
<a name="tongket"></a>
## III. Summary:

Watch Video here: 

- [How to Install and configure Samba on Ubuntu 20.04 Part 1:  Public folder](https://youtu.be/2o5zgA8ml38)
- [How to configure and Install Samba on Ubuntu 20.04 Part2: Private Share](https://youtu.be/6s9ZEp3xS94)

**Contact me:**
- Email: manhhungbl@gmail.com
- Skype: spyerx3
- Youtube Channel: youtube.com/howtoused

Thank you very much!
