<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
In this lab I am going to take the steps to create an Active Directory home lab environment using Oracle Virtual Box. Configuring and running this lab will definitely help develop my understanding of how Active Directory and Windows networking works in a hands on way.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Oracle Virtual Box</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Server 2019 installed: <br/>
<img src="https://i.imgur.com/B382zVh.png" height="80%" width="80%" alt="Server 2019 installed"/>
<br />
<br />
Setting up NICs (internet and internal facing):  <br/>
<img src="https://i.imgur.com/aR6LUlM.png" height="80%" width="80%" alt="Setting up NICs (internet and internal facing)"/>
<br />
<br />
Renaming PC to DC Domain Controller: <br/>
<img src="https://i.imgur.com/sTH6ncR.png" height="80%" width="80%" alt="Renaming PC to DC Domain Controller"/>
<br />
<br />
Assigning an internal IP address:  <br/>
<img src="https://i.imgur.com/Dv572ut.png" height="80%" width="80%" alt="Assigning an internal IP address"/>
<br />
<br />
Adding Active Directory Domain Services:  <br/>
<img src="https://i.imgur.com/Ivw4CrA.png" height="80%" width="80%" alt="Adding Active Directory Domain Services"/>
<br />
<br />
Add my own domain admin account a-:  <br/>
<img src="https://i.imgur.com/UqABrLJ.png" height="80%" width="80%" alt="Add my own domain admin account a-"/>
<img src="https://i.imgur.com/ksdukxr.png" height="80%" width="80%">
<br />
<br />
Installing Remote Access Server and NAT:  <br/>
<img src="https://i.imgur.com/5VPYC9t.png" height="80%" width="80%" alt="Installing Remote Access Server and NAT"/>
<img src="https://i.imgur.com/GdWmDSg.png" height="80%" width="80%">
<br />
<br />
DHCP Scope and DNS server:  <br/>
<img src="https://i.imgur.com/u2GPU4B.png" height="80%" width="80%" alt="DHCP Scope and DNS server"/>
<img src="https://i.imgur.com/KVX9stQ.png" height="80%" width="80%">
<br />
<br />
Enabling (Normal browsing):  <br/>
<img src="https://i.imgur.com/PblkOH8.png" height="80%" width="80%" alt="Enabling (Normal browsing)"/>
<br />
<br />
Powershell script adding 1000 users:  <br/>
<img src="https://i.imgur.com/xlXD7WH.png" height="80%" width="80%" alt="Powershell script adding 1000 users"/>
<img src="https://i.imgur.com/vyy7MhZ.png" height="80%" width="80%">
<img src="https://i.imgur.com/eIxn1sK.png" height="80%" width="80%">
<br />
<br />
Configure Client 1 to connect to internal network adapter as well as install windows 10 onto the Client:  <br/>
<img src="https://i.imgur.com/INyRBtW.png" height="80%" width="80%" alt="Configure Client 1 to connect to internal network adapter as well as install windows 10 onto the Client"/>
<br />
<br />
Adding default gateway for Client1 user:  <br/>
<img src="https://i.imgur.com/Te2MHSL.png" height="80%" width="80%" alt="Adding default gateway for Client1 user"/>
<img src="https://i.imgur.com/9NN6Vxm.png" height="80%" width="80%">
<br />
<br />
Ping mydomain.com to varify everthing is working properly:  <br/>
<img src="https://i.imgur.com/HLfFU0r.png" height="80%" width="80%" alt="Ping mydomain.com to varify everthing is working properly"/>
<br />
<br />
Joining the domain as User1:  <br/>
<img src="https://i.imgur.com/U5NquEF.png" height="80%" width="80%" alt="Joining the domain as User1"/>
<img src="https://i.imgur.com/3xKah8y.png" height="80%" width="80%">
<img src="https://i.imgur.com/qnTYnzs.png" height="80%" width="80%">
<br />
<br />
Logging into client computer:  <br/>
<img src="https://i.imgur.com/U5NquEF.png" height="80%" width="80%" alt="Logging into client computer"/>
<img src="https://i.imgur.com/TLufgyU.png" height="80%" width="80%">
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
