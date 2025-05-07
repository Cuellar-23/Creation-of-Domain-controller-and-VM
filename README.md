<h1>Creation-of-Domain-controller-and-VM</h1>

<h2>Description</h2>
 In this project I will create a simulated enterprise network by configuring two virtual machines (VMs): one running Windows Server 2022 and the other Windows 10 using Hyper-V. Once both machines were created in Hyper-V, I configured the Machines, assigning computer names and IP addresses. After that I performed a ping test ensuring both machines can communicate with one another. Next, I installed the Active Directory Domain Services (AD DS) role on the Windows Server Machine, promoted it to a domain controller, and joined the Windows 10 Machine to the newly created domain.  
<br />

<h2>Project walk-through:</h2>

<p align="center">
Both Virtual Machines created in Hyper-V : <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20084934.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Specifications for DC01 (VM running Windows Server 2022):  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20085346.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Specifications for PC01 (VM running Windows 10)  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20085821.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Ping test between DC01 (10.0.0.100) and PC01 (10.0.0.101):  <br/>
<img src="https://github.com/Cuellar-23/Creation-of-Domain-controller-and-VM/blob/main/Screenshot%202025-05-07%20093637.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add user to Security Groups and Administrators via PowerShell:  <br/>
<img src="https://github.com/Cuellar-23/Active-Directory-design-with-PowerShell/blob/main/Screenshot%202025-05-06%20141335.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add Computers to domain and assign to Organizational unit via PowerShell:  <br/>
<img src="https://github.com/Cuellar-23/Active-Directory-design-with-PowerShell/blob/main/Screenshot%202025-05-06%20141536.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
