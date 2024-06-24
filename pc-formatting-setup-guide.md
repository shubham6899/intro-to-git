# PC Formatting and Setup Guide

## 1. Backup Your Data

Before formatting your PC, ensure all important data is backed up to an external drive or cloud storage.

- **Documents:** Important files, academic work, personal documents.
- **Photos and Videos:** Personal photos and videos.
- **Music and Other Media:** Music collections, movies, etc.
- **Application Data:** Browser bookmarks, email archives, etc.

## 2. Create a Bootable USB Drive

You will need a bootable USB drive with the installation files for your operating system.

### For Windows:

- Download Windows 10/11 ISO: Download from the [official Microsoft website](https://www.microsoft.com/en-us/software-download/windows10).
- **Create Bootable USB:**
  - Use the Media Creation Tool provided by Microsoft.
  - Follow the instructions to create a bootable USB drive.

### For macOS:

- Download macOS Installer: Download from the Mac App Store.
- **Create Bootable USB:**
  - Use the `createinstallmedia` command in Terminal.
  - Follow the instructions on the [Apple support website](https://support.apple.com/en-us/HT201372).

## 3. Format and Install the Operating System

### For Windows:

1. Insert the Bootable USB and restart your computer.
2. **Enter BIOS/UEFI:** Press the appropriate key (often F2, F12, DEL, or ESC) during boot to enter the BIOS/UEFI settings.
3. **Set USB as Boot Device:** Change the boot order to prioritize the USB drive.
4. **Save and Exit:** The PC will restart and boot from the USB.
5. **Install Windows:**
   - Follow the on-screen instructions to install Windows.
   - When prompted, select "Custom: Install Windows only (advanced)".
   - Delete all partitions to fully format the drive.
   - Create new partitions as needed (e.g., for system, work, personal, and backups).
   - Proceed with the installation.

### For macOS:

1. Insert the Bootable USB and restart your Mac.
2. **Enter Startup Manager:** Hold the Option (⌥) key during startup.
3. **Select the USB Drive:** Choose the bootable USB drive from the options.
4. **Install macOS:**
   - Open Disk Utility from the macOS Utilities window.
   - Select your main disk and click "Erase".
   - Format the disk using APFS or Mac OS Extended (Journaled).
   - Close Disk Utility and select "Install macOS".
   - Follow the on-screen instructions to complete the installation.

## 4. Initial Setup

After installing the operating system, follow the setup wizard to configure basic settings:

- **Language and Region**
- **Network Connection**
- **User Account Creation**
- **Privacy Settings**

## 5. Install Essential Software

### Windows:

- **Web Browser:** Chrome, Firefox, etc.
- **Security Software:** Windows Defender or a third-party antivirus.
- **Productivity Tools:** Microsoft Office, Google Drive, etc.
- **Programming Tools:** IDEs (Visual Studio Code, IntelliJ IDEA), Git, etc.
- **Utilities:** File compression tools (7-Zip, WinRAR), media players (VLC), etc.

### macOS:

- **Web Browser:** Chrome, Firefox, Safari.
- **Security Software:** Built-in macOS security features or third-party options.
- **Productivity Tools:** Microsoft Office, iWork, Google Drive.
- **Programming Tools:** Xcode, Visual Studio Code, Git, etc.
- **Utilities:** File compression tools (Keka), media players (VLC), etc.

## 6. Set Up Folder Structure

**Disk Partitioning (If Needed):**

- **Windows:** Use Disk Management to create additional partitions (Right-click Start > Disk Management).
- **macOS:** Use Disk Utility to create additional volumes.

## 7. Set Up Backup and Sync

- **Cloud Services:** Set up Google Drive, Dropbox, or OneDrive.
- **External Drives:** Configure external hard drives for offline backups.
- **Automated Backups:** Use tools like Acronis True Image or built-in OS backup utilities to schedule regular backups.

## 8. Final Steps

- **Install Additional Software:** Based on your specific needs (e.g., music software, photography tools).
- **Configure Settings:** Customize your system settings, themes, and preferences.
- **Test Everything:** Ensure all software and hardware are working correctly.

## Summary

Following these steps will help you format your PC and set it up efficiently for a fresh start.
