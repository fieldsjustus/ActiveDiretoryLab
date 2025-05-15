<h1>Configure Domain Controller and Manage Users & Groups in Active Directory</h1>

 ### [Lab Instructions](https://app.cybrary.it/browse/virtual-lab/active-directory-basics?queryID=undefined&objectID=70965)

<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Service Manager</b>

<h2>Environments Used </h2>

- <b>Windows 22 GUI Server</b> 

<h2>Program walk-through:</h2>

<p align="center">
Install Active Directory Domain Services on Windows 2022 Server: <br/>
<img width="752" alt="Image" src="https://github.com/user-attachments/assets/1f4c0b70-260f-4cbc-8728-fdc7dc213d3c" />
<br />
<br />
Promote Server to a domain controller:  <br/>
<img <img width="752" alt="Image" src="https://github.com/user-attachments/assets/0db3ed2b-d6a4-4ae7-af56-a6d0d8e51b8a" />/>
<br />
<br />
Deploy Configuration: <br/>
<img <img width="754" alt="Image" src="https://github.com/user-attachments/assets/015a7892-2a4b-47ec-beed-d66f998cb38a" />/>
<br />
<br />
Install Active Directory Domain Services via Powershell:  <br/>
<img <img width="751" alt="Image" src="https://github.com/user-attachments/assets/20428097-b088-4c88-8d42-61d4ce95b1af" />/>
<br />
<br />
Create a Domain Controller using Powershell:  <br/>
<img <img width="751" alt="Image" src="https://github.com/user-attachments/assets/53232fec-4ddd-48c6-a4b3-925193083f14" />/>
<br />
<br />
Create Organizational Unit:  <br/>
<img <img width="749" alt="Image" src="https://github.com/user-attachments/assets/879aefba-9c9a-4dc0-98bc-664b33ab11e4" />/>
<br />
<br />
Add users to OU:  <br/>
<img <img width="752" alt="Image" src="https://github.com/user-attachments/assets/f6fd7b6f-6eda-45c5-b463-09813491ea27" />"/>
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
