# Install Virtual Box:
To check if virtualization is enabled and enable it if necessary. Then, follow these steps:

#### 1. Open Task Manager:

Press Ctrl + Shift + Esc or Right-click the taskbar and select Task Manager.
Navigate to the Performance Tab:

In the Task Manager window, click the Performance tab located on the left-hand side.
#### 2. Check Virtualization Status:

Look at the bottom right of the window under the CPU section.
If you see Virtualization: Disabled, it means virtualization is currently turned off.
<div style="text-align: center;">
<img src="./image/enablingvirtualizationfromtaskmanager.png" alt="Enable Virtualization" width="600">
</div>


# Get started with VirtualBox and Lubuntu:

#### 1. Download and Install VirtualBox:
Visit the [VirtualBox Downloads page](https://www.virtualbox.org/wiki/Downloads).
On the page, select the appropriate version for your operating system (Windows, macOS, Linux, etc.).
Once the download is complete, open the installer and follow the on-screen instructions to install VirtualBox on your computer.
#### 2. Download the Latest Version of Lubuntu:
After installing VirtualBox, go to the [Lubuntu Download page](https://lubuntu.me/downloads/).
Click on the latest version of Lubuntu to start downloading the ISO file.
Don't Install Lubuntu now.
#### 3. Create a folder:
Create a new folder on a drive other than C to be safe. Name the folder exactly as "Virtual Box" (be sure to match the capitalization and spelling).
<div style="text-align: center;">
<img src="./image/folder.jpeg" alt="Enable Virtualization" width="600">
</div>

#### 4. Create Virtual Machine(Host):
Launch the VirtualBox application on your system.Click on "New".

In the dialog box that appears, enter the name as "host".(Be careful with the naming—do not change it later.)

VirtualBox may auto-fill some settings like the operating system and version based on the name. If not, set them manually:

###### Type: Linux
###### Subtype: Ubuntu
###### Version: Ubuntu (32-bit or 64-bit, depending on your ISO)

In the "Folder" field, browse to the folder you just created to store the virtual machine files and select it.
In the "ISO Image" field, browse to the location where you downloaded the lubuntu.iso file and select the file.

Allocate Resources (Optional):

VirtualBox might ask you to configure resources like suggest a recommended memory size for Lubuntu. You can either accept the default value or adjust it based on your system's capacity. For disk space, follow the guided steps to create a virtual hard disk and choose the default settings unless you have specific requirements.

After reviewing the configuration, click "Finish" to create the virtual machine.

<div style="text-align: center;">
<img src="./image/setuphost.jpeg" alt="Enable Virtualization" width="600">
</div>

#### 5. Install Lubuntu
In VirtualBox, select the host virtual machine you just created and click Start.

<div style="text-align: center;">
<img src="./image/start.jpeg" alt="Enable Virtualization" width="600">
</div>

When the boot menu appears, use the arrow keys to select "Try or Install Lubuntu" and press Enter.
In the window that appears, choose "Install Lubuntu" to begin the installation process.

<div style="text-align: center;">
<img src="./image/installLubuntu.jpeg" alt="Enable Virtualization" width="600">
</div>

After the installation begins, you'll see a Welcome page. Select your preferred language, Location, and Keyboard Layout.

Choose Normal Installation for a full Lubuntu installation.
When prompted for partitioning options, select Erase disk and install Lubuntu. Confirm if you’re asked to erase the disk.

<div style="text-align: center;">
<img src="./image/erasedisk.jpg" alt="Enable Virtualization" width="600">
</div>

In the user configuration section, enter a short user name (e.g., user), set the password as 1234, confirm the password, and click Continue.

<div style="text-align: center;">
<img src="./image/userinfo.jpg" alt="Enable Virtualization" width="600">
</div>

Click Install to begin the installation process. Once the installation is done, click Finish.
Restart the virtual machine if prompted.

<div style="text-align: center;">
<img src="./image/finish.jpg" alt="Enable Virtualization" width="600">
</div>




