<h1>Metasploitable 2 HomeLab</h1>

<h2>Description</h2>
This project explains how to setup Metasploitable 2 as a HomeLab project. I have provided instructions for the user on how to correctly download and install Metasploitable 2 as a HomeLab test environment using a virtual machine (Oracle VM VirtualBox).
<br />


<h2>Utilities Used</h2>

- <b>Oracle VM VirtualBox</b> 


<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Skills Leanred </h2>

- Creating a new VirtualBox profile
- Basic Linux Shell commands



<h2>Instructions:</h2>

<p align="center">
First, you'll need to download the Metasploitable file from the link provided: https://sourceforge.net/projects/metasploitable/ <br/>
<img src="https://imgur.com/pLDBULT.png" height="80%" width="80%" alt="Metasploit 2 HomeLab steps"/>
<br />
<br />
You'll then need to manually create a new virtual machine in VirtualBox. <br/>(if you dont already have VirtualBox installed, use the provided link to the download file): <br/>https://www.virtualbox.org/wiki/Downloads <br/>
<br />
<br />
Next, Click the NEW button at the top, and copy the settings from the below screenshot: <br/>
<img src="https://imgur.com/zrrK8KR.png" height="80%" width="80%" alt="Metasploit 2 HomeLab steps"/>
<br />
<br />
To import Metasploitable 2, select the “Use an existing virtual hard disk file” and find the Metasploitable.vmdk file, that is inside the .zip file you downloaded earlier:  <br/>
<img src="https://imgur.com/c0Os7xW.png" height="80%" width="80%" alt="Metasploit 2 HomeLab steps"/>
<br />
<br />
Once the virtual machine has successfully been created, you should be able to boot it. <br/> 
 Once the boot up process has completed, it'll prompt you for a username and password. By default, they are both set to "msfadmin":  <br/>
<img src="https://imgur.com/6RNx3ZY.png" height="80%" width="80%" alt="Metasploit 2 HomeLab steps"/>
<br />
<br />
Run the command "ifconfig" to confirm that an ip address has been configured: <br/>
 <img src="https://imgur.com/bAnu385.png" height="80%" width="80%" alt="Metasploit 2 HomeLab steps"/>
<br />
<br />
CONGRATULATIONS! <br>
 you have now successfully installed Metasploitable 2 on your virtual machine  <br/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
