<h1>Active Directory Lab</h1>

<h2>Description</h2>
Active Directory Administration: Powershell: Automated provision, maintinging, and deprovisioning user accounts. Setting up Remote Access Server (RAS) features to support NAT/PAT. Implementation and maintenance of Windows DNS and DHCP services. Configuration of Windows File Servers with implementation of quotas and NTFS permissions.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>Oracle VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>
- <b>Windows 10</b>

<h2>Program walk-through:</h2>

<p align="center">
Download and install Oracle VirtualBox to create virtual machines: <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/6b6f7375-e902-48fc-be1a-0dcacb3409ea"/>
<br />
<br />
Create a domain controller, install Windows Server 2019:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/29e350bd-46f4-46a9-90ff-4cff711199e5"/>
<br />
<br />
Install Windows Server 2019:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/d4cfe5b5-e475-4c38-b48a-2ecf8d711641"/>
<br />
<br />
Install Active Directory Domain Services:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/5b10a9de-705d-4722-97d9-efdde39dde3e"/>
<br />
<br />
Add DNS feature:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/0e87b328-58b4-4cf8-8040-73c5d2cc00b7"/>
<br />
<br />
Create a dedicated domain: <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/0aa74c75-6108-4b67-bd3d-270af3dd0a33"/>
<br />
<br />
Create a new organizational unit:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/06394d4f-ea45-4492-a32a-6f1e0ff499d5"/>
<br />
<br />
Distinguish Intranet from Internet, change name:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/c595be60-2eae-48d8-8e07-ad143865a53a"/>
<br />
<br />
Create a domain administrator:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/dd2a4fcc-63e2-4c07-8f72-9d985a04bdda"/>
<br />
<br />
Add routing and remote access:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/54368da0-137a-451d-8d32-ba1e9a22c927"/>
<br />
<br />
Setup a DHCP Server on the domain:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/88f53108-5777-47ef-b350-db669f33ecaa"/>
<br />
<br />
Run source code for Powershell script to create 1,000 users:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/9e4319e7-f5ce-45c2-821a-14e233b0fae8"/>
<br />
<br />
Create a new client virtual machine and install Windows 10 Pro:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/5676c4a4-f268-4c42-89dc-167331acb500"/>
<br />
<br />
Add the domain controller to client, check connection and active directory users:  <br/>
<img src="https://github.com/urmomtookurscreentime/ActiveDirectoryLab/assets/146014829/8a874207-7913-4aff-8b1a-ac1644477b20"/>
<br />
<br />
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
