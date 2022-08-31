<h1>Part II: Command Line Tools</h1>



<h2>Description</h2>
In this lab, I learned to use the nslookup, arp, route, and netstat commands. The nslookup command resolves an FQDN (fully qualified domain name) to an IP (Internet Protocol) address on Microsoft Windows and UNIX (uniplexed information computing system) hosts. The arp command is used in either a Microsoft Windows or UNIX environment to see what Layer 2 MAC (media access protocol) addresses correspond to Layer 3 IP addresses. The route command is used to add, modify, or delete routes in the IP routing tables of Microsoft Windows and UNIX hosts. The netstat command displays a variety of information about IP-based connections on a Windows or UNIX host. 


<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 


<h2>Languages and Utilities</h2>

- <b>Windows Powershell<b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop go to the start and from there open up windows powershell: <br/>
<img src="https://i.postimg.cc/1tD4z97x/Screen-Shot-2022-08-31-at-10-52-36-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br>
Type in "nslookup" and any website you wish (I chose to ping www.google.com):<br>
<img src="https://i.postimg.cc/QCPwCW6S/Screen-Shot-2022-08-31-at-11-13-57-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now I will try the "arp -a" command to show what MAC addresses have been learned on the listed IP addresses:</br>
<img src="https://i.postimg.cc/25SQ9jF7/Screen-Shot-2022-08-31-at-11-17-38-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Now lets try the "route print" command to display the contents of of a PC's routing table :  <br/>
<img src="https://i.postimg.cc/pVhg1Rsv/Screen-Shot-2022-08-31-at-11-20-47-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />


<br />
Now I will try the "netstat" command to show the path taken by the packet on an IP network from th esource to its detination :  <br/>
<img src="https://i.postimg.cc/zv7WF9bc/Screen-Shot-2022-08-31-at-11-23-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />



<br />
Now lets try the "netstat -b" command to show the name of the program that opened the session :  <br/>
<img src="https://i.postimg.cc/jCVVvkpy/Screen-Shot-2022-08-31-at-11-25-11-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
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
