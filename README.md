<p align="center">
<img src="https://i.imgur.com/Aja9D5E.jpeg" />
</p>


<h1>VirtualBox - Prerequisites and Installation</h1>
VirtualBox supports Windows, macOS, Linux, and Solaris. In this instance, I will be using the Ubunto distribution of Linux. <br />


<h2>Environments and Technologies Used</h2>

- VirtualBox
- VirtualBox Extension Pack
- Ubuntu

<h2>Operating System Used</h2>

- Linux</b> 

<h2>Prerequisites</h2>

- 2GB of RAM minimum (4GB recommended)
- Multicore processor
- Sufficient hard drive space (the amount depends on your virtual machine usage)

<h2>Installation Steps</h2>



<h2>Installation Steps</h2> <p> <img src="https://i.imgur.com/L946ZHg.png" /> </p> <p> Download VirtualBox from <a href="https://www.virtualbox.org/wiki/Downloads">here</a>. Download the Ubuntu desktop image from <a href="https://ubuntu.com/download/desktop">here</a>. The Ubuntu image includes the entire operating system along with an installer. VirtualBox will handle the Ubuntu installation process.
Open VirtualBox and click the Tools button on the left. Then, select the Welcome tab. Click the New button to open the screen shown above. Here, choose a name for the virtual machine (a descriptive name is recommended).

Click the dropdown button next to ISO Image, navigate to the location where you downloaded the Ubuntu image, and select the file.
<b>Important:</b> Select the Skip Unattended Installation checkbox! If this option is not checked, VirtualBox will attempt to install everything automatically, which may lead to errors or unnecessary issues during installation. Click Next to proceed.

</p> <br /> <p> <img src="https://i.imgur.com/15Jnjqr.png" "/> <img src="https://i.imgur.com/aRfOK9o.png" /> </p> <p> These screens allow you to configure the hardware for the virtual machine. Ideally, allocate at least **512MB of base memory**, though more is recommended depending on your computer's resources. The more memory you allocate, the better the virtual machine's performance will be.
For processors, allocate at least 2 CPUs if your system supports it. Click Next to proceed.

For the virtual hard disk, allocate an amount of memory you are comfortable dedicating to the virtual machine. <b>Note:</b> The virtual machine will only use the allocated space as needed. For example, if you assign 100GB, the physical hard drive will only use that amount if 100GB of data is installed on the virtual machine. Click Next, review your configuration summary, and if satisfied, click Finish. Use Back to make changes if needed.

</p> <br /> <p> <img src="https://i.imgur.com/M7zeB2F.png" /> </p> <p> Finally, click the **Start** button to launch the virtual machine. </p> <br />
