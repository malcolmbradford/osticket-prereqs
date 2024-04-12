# osticket-prereqs<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://youtu.be/dEvGaxOgqf0?si=LA1ol004g0BYSvwq)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows
- Install MySQL server
- OsTicket installer
- Install C++
- Config persmissons 

<h2>Installation Steps</h2>

![image](https://github.com/kayetech84/osticket-prereqs/assets/153541024/2659b6e4-0807-416b-addb-f2ebe17ef33d)



</p>
<p>
First thing, create VM in Azure portal. Grab public IP address from VM open remote desktop connection.  Install/Enable IIS in Windows / CGI and common HTTP features. Install PHP for IIS. Install rewrite module. Install VC redist. Successfully installed IIS in Windows.
</p>
<br />

![image](https://github.com/kayetech84/osticket-prereqs/assets/153541024/fdbd6a19-bce9-4113-9ca5-f5577eb902d5)

</p>
<p>
Ready to insall MySQL. When installing we will do Typical setup-> Launch Configuration Wizard (after install) -> Standard Configuration
</p>
<br />

![image](https://github.com/kayetech84/osticket-prereqs/assets/153541024/ec297d2d-3173-468f-babb-21e6a218932e)


</p>
<p>
OsTicket has been installed, now setup it up to be used. There are some extensions to be enabled. Rename the ost-sampleconfig.php file. Assign new permissions to everyone. Then continue on to setting up osTicket in browser. The last installation file will be Heidi SQL. 
</p>


![image](https://github.com/kayetech84/osticket-prereqs/assets/153541024/9c2b4500-0c23-402d-ac83-1511c0ab5bec)

<p>
OsTicket has been installed; now setup it up to be used. There are some extensions to be enabled. Rename the ost-sampleconfig.php file. Assign new permissions to everyone. Then continue on to setting up osTicket in browser. The last installation file will be Heidi SQL. 


![image](https://github.com/kayetech84/osticket-prereqs/assets/153541024/f14d6609-3101-452a-b922-5f55749d8b21)

</p>
<p>
Installed w/o error. Lets began to set up some tickets. 
</p>
<br />
