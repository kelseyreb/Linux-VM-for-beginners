# Linux-VM-for-beginners
Linux VM walk through with explanations

1. First begin by downloading a Virtual Machine Manager. If you have Windows 11 Pro you could download HyperVisor and create a Virtual Machine that way OR you can download one off the internet. I downloaded one at this website. https://www.virtualbox.org/wiki/Downloads

2. I then downloaded a debian Net install through this website. –	https://www.debian.org/CD/netinst/

3. This is what your Virtual machine box will first look like when you start it. 
![Linux VM](https://raw.githubusercontent.com/kelseyreb/Linux-VM-for-beginners/refs/heads/main/Screenshot%202025-10-06%20140002.png)

4. You’re going to click new. The new button is a blue spiked sphere. This is what it would look like.
![1](https://raw.githubusercontent.com/kelseyreb/Linux-VM-for-beginners/refs/heads/main/Screenshot%202025-10-06%20143148.png)

5. From here Name your VM name, I am going to name mine Debian VM.
![2](https://raw.githubusercontent.com/kelseyreb/Linux-VM-for-beginners/refs/heads/main/Screenshot%202025-10-06%20143254.png)

6. I am going to leave the VM location where it is, feel free to put the location anywhere you would like. 

7. For the ISO image you are going to select the Debian Image downloaded in the first step
![3](https://raw.githubusercontent.com/kelseyreb/Linux-VM-for-beginners/refs/heads/images/Screenshot%202025-10-06%20143315.png)

8. Now click on the “Set up unattended guest OS installation” this is what it will look like. 
![4](https://raw.githubusercontent.com/kelseyreb/Linux-VM-for-beginners/refs/heads/images/Screenshot%202025-10-06%20143648.png)

9.	First thing we are going to change the User name – set it as whatever you want, I recommend setting it as your first name. Ensure the username is lowercase. Then we will set up the password. Keep this super simple for this example and insert “1234” Real world scenario you will need to create a more secure password. ![5](
10.For the Host Name, I am just going to name it “debianVM”.
11. Keep the default settings for both ‘Specify virtual hard disk’ AND ‘Create a New Virtual Hard Disk’ Then click finish.
12. Your VM will automatically start downloading the ISO file. This process will take between 5-10 minutes. When the software is done running login using the username and password created above in step 9.
13. When you first logon, you will get this screen. If you want to take the tour feel free, we are going to be skipping this step.
14.	First locate the terminal application, click the 3X3 box  this is what it looks like.
15.	The terminal application is located on the very bottom row
16.	This is how the command line looks like.
17.	First command we are going to run is ‘su’.  ‘su’ switches the user to “superuser” mode this is like being the administrator of the system. Superuser commands need special privileges to make changes. This also shows principle of least privilege with ensuring that administrative rights are separated. For the password you will enter in the password used to login. Be careful it does not show you. You will know you are in the SuperUser mode when you have the username# as shown below
18.Second command we are going to run is ‘apt-get update’ this refreshes the list of available software and updates.
19.	Next command we are going to run is ‘apt-get upgrade’. The installs the latest versions of software already on the system.
20.	Now lets make the system say hello and also to test to see if the system is working  and responding correctly.
21.Now the next few commands we are going to be gathering system information. First lets check what version of linux we are running. Use the command ‘cat /proc/version’ This shows us the name and version we are operating on. 
