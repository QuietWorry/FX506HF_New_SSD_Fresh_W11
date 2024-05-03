# FX506HF_New_SSD_Fresh_W11

On separate PC [you will need the laptop a separate PC or Mac and two usb flash drives (>= 8GB)]

Windows 11 Official Setup:
https://www.microsoft.com/software-download/windows11
Choose “create … instillation media” and download
Follow instruction to mount to USB
Install drive to powered off Laptop

Drivers for Windows 11 Setup:
You’ll need the intel storage driver for the Windows setup to recognize the SSD
Go to ASUS.com/support and look up your FX506HF, go under “drivers & utilities”, then select show all for the “Chipset” drivers and download “IRST” driver
Run .exe and extract to a second flash drive
Keep second drive ready, but not installed on Laptop


On New Laptop [*** Remember to remove second flash drive with IRST driver when instructed]

Boot Windows 11 Setup USB Media:
With only the USB containing the Windows Setup, power on the Laptop
If the Windows Setup UI does not appear, go to bios and move the USB drive to the top of the boot order
This may be when the laptop goes back to the setup stage I left it at, try out some of the Setup features to see if that outcome is possible
If not, start a new Windows installation
You will be asked to choose a C: drive. If the SSD does not show up, which is likely, select “load driver”
Install the second USB (when to do this is up to how Windows setup recognizes the drive) and search its contents with the Setup Load Driver Menu. With “display only compatible drivers” selected at the bottom, there should be at least one driver option to load. If there are more select all
Now the SSD should be recognized, delete what volumes it allows you to, then you may need to create a new partition to select for the C: Drive. WAIT! Before you confirm the SSD partition you’re going to use you NEED to remove the second USB drive with the IRST driver (I spent a day making this mistake, even though all advice told me to remove it the only things plugged into the laptop should be the power cord and USB with windows Setup)
Then continue with Windows install

Download and Install all Motherboard Drivers for full peripheral functionality:
Go back to ASUS.com/support and look up the FX506HF (https://www.asus.com/supportonly/fx506hf/helpdesk_download/) and download all drivers (and software that you want, the apps make keeping the Laptop up to date easy, but do have performance loads) Make sure you are clicking the “show all” to display all drivers in each category. Some drivers are duplicates of older versions, just download the latest versions.
Boot up windows, download these driver install files and run each of them individually then restart
I hope this works, if not this is just the most full-proof solution I have, but I still have more ideas

P.S. I wrote this pretty fast, let me know if you need more detail or just call (I have one thing to do today between 4 and 5:30, but free any other time and tomorrow)
