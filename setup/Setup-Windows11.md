# Setup Windows 11 

This section demonstrates how to download and install **Windows 11 Enterprise** and set it up in **VirtualBox**

---

### Step 1 Download Windows 11 Enterprise ISO

1. Navigate to: https://www.microsoft.com/en-us/evalcenter
2. At the top, click **Windows** ->Select  **Windows Enterprise 11**
3. Click **Download the ISO**
4. Complete the registration form for the free trail
5. Click **Download Now** after registration
6. Under the **English** section, select **64-bit edition**
7. Save the ISO file to your desired location
 
---

### Step 2 Create Virtual Machine in VirtualBox

1. Lauch **VirtualBox**
2. Click **New**
3. Configure the VM:
    **Name**: Windows 11 Enterprise 
    **ISO Image**: Select the downloaded ISO file 
    Click **SKIP unattended Installation**
4. Click **Next**
5. Configure hardware:
    - Leave default settings (or adjust if needed)
    - Click **Next**
6. Configure virtual hard disk:
    - Leave default settings 
    - Click **Next**
7. Click **Finish**

---

## Step 3 Install Windows 11 Enterprise
1. Click on **Windows 11 Enterprise VM** 
2. Click **Start**
3. Click inside the VM window to begin setup
4. Follow the installation steps:
    - Select **Language and keyboard setup (e.g., English , US)**
    - Accept **License Terms** -> Click Next
    - Select **Custom: Install Windows Only**
    - Choose the default drive -> Click **Next**
5. Wait for Windows to install

---

### Step 4 Complete Windows Setup

1.  Configure inital settings:
    - Select **Region** (e.g., United States)
    - Select **Keyboard Layout** (e.g., US)
    - Skip adding a second keyboard layout
2. Account setup:
    - Click **Sign-in option** -> Select **Domain join instead**
    - Enter a usernmae -> Click **Next**
    - Enter a password -> Click **Next**
    - Set and answer security questions
3. Privacy settings:
    - Disable unnecessary options as desired 

4. Once setup is complete, log in to Windows

---

### Step 5 Install Guest Additions

1. In the VirtualBox menu, click:
**Devices -> Insert Guest Additions CD Image**
2. Open **File Explorer** inside the VM
3. Navigate to the mounted drive
4. Right-click **VBoxWindowsAdditions-amd64** → Select **Run as administrator**
5. Click **Yes** when prompted
6. In the setup wizard:
    - Accept default settings
    - Click **Install**
7. Click **Finish**, then select **Reboot Now**

---

### Step 6 Adjust Display Settings
After reboot:
1. Log back into the VM
2. In the VirtualBox menu, click **View**
3. Select **Auto-resize Guest Display**
4. Enable full screen:
    Click **View -> Full Screen Mode**
