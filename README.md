# Azure-File-Share-Project
In this project, I used the Azure portal and CLI to create a File Share to upload local files to my Azure Directory.

<h2>Environments Used </h2>

- <b>Azure Portal</b> 

- <b>Azure CLI</b> 

<h2>Program walk-through:</h2>

<p align="center">
 I started this project by using the Azure CLI to create an Azure resource group named datacenterhq1: <br/>
<img src="https://i.imgur.com/rZxUwli.png" height="80%" width="80%" />
<br />
<br />
I then verified the creation of datacenterhq1 in the portal:  <br/>
<img src="https://i.imgur.com/lfqKXlc.png" height="80%" width="80%" />
<br />
<br />
Once the resource group was created I used the CLI to create a storage account named storesyncrsa:  <br/>
 <img src="https://i.imgur.com/hk1TKqq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I then verified the creation of storesyncrsa in the portal:  <br/>
<img src="https://i.imgur.com/z3JOBcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
<br />
After creating the storage account storesyncrsa, I started the creation of the file share fileshare1rsa:  <br/>
<img src="https://i.imgur.com/z3JOBcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I verified the creation of the file share fileshare1rsa in the portal.:  <br/>
<img src="https://i.imgur.com/z3JOBcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br /> 
I then created a new directory named rsadirectory at the root of fileshare1rsa using the portal:  <br/>
<img src="https://i.imgur.com/z3JOBcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Once the directory was created I then uploaded my local files to it using the portal:  <br/>
<img src="https://i.imgur.com/z3JOBcf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
