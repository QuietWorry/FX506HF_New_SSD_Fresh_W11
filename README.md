# Windows 11 Installation Guide for ASUS FX506HF with Fresh NVME SSD

This guide will help you install Windows 11 on your ASUS FX506HF laptop using a USB flash drive. Follow these steps carefully to ensure a successful installation.

## Prerequisites

- A separate PC or Mac
- Two USB flash drives (8GB or larger)

## Step 1: Create Windows 11 Installation Media

1. Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
2. Choose "Create Windows 11 installation media" and download the tool.
3. Follow the instructions to mount the Windows 11 image onto your USB flash drive.
4. Ensure the USB drive is inserted into the powered-off laptop.

## Step 2: Prepare Drivers for Windows 11

1. Download the Intel Storage Driver from [ASUS support](https://www.asus.com/support). Search for FX506HF under "Drivers & Utilities," then find the "IRST" driver in the "Chipset" section.
2. Run the downloaded `.exe` file and extract the contents to a second USB flash drive.
3. Keep this drive ready but do not insert it into the laptop yet.

## Step 3: Install Windows 11

1. With only the Windows Setup USB inserted, power on the laptop.
2. If the setup does not start, access the BIOS and prioritize the USB drive in the boot order.
3. Follow the on-screen instructions until you reach the point where you are asked to select a drive.
4. If the SSD is not visible, choose "Load Driver" and insert the second USB flash drive when prompted.
5. Search its contents for compatible drivers, select all that appear, and load them.
6. Delete any existing partitions on the SSD if possible, then create a new partition for Windows.
7. **Important**: Remove the second USB drive with the IRST driver before confirming the SSD partition.

## Step 4: Install Motherboard Drivers

1. Once Windows is installed, return to the [ASUS support page](https://www.asus.com/supportonly/fx506hf/helpdesk_download/) and download all necessary drivers and any desired software.
2. Install each driver individually and restart the laptop as needed.

## Notes

- Ensure you follow these steps carefully. If there are issues, I have more solutions available.
- I'm available for assistance if needed (except today between 4 and 5:30 PM). Feel free to call.
