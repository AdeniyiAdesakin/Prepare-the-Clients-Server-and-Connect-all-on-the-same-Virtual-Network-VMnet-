<h1>Preparing the Clients/Server and Connecting all on the same Virtual Network(VMnet)</h1>
<p>This tutorial outlines the preparation of the client and server VMs which includes computer name change, IP address/DNS server address configuration.<br /></p>

<h2>*Change the Name and IP Addresses of the VMs - Windows Server 2019</h2>
<p>1. To change the name of Windows Server 2019 VM, go to file exporer, right click on “This PC” and go to properties. In the ‘Computer name, domain and workgroup settings” window, click on “change settings”</p>
<p align="center"><img src="https://i.imgur.com/aiRdD2p.png" height="50%" width="50%" alt="image"/>
<p align="center"><img src="https://i.imgur.com/xiciKuj.png" height="50%" width="50%" alt="image"/>

<p>2. On the System’s properties’ page, click the Change button. On the computer name/domain changes screen, input the VM’s name and click OK to save.</p>
<p align="center"><img src="https://i.imgur.com/inliumE.png" height="50%" width="50%" alt="image"/>
<p align="center"><img src="https://i.imgur.com/GDp5x2q.png" height="50%" width="50%" alt="image"/>

<p>3. To change the IP address of Windows Server 2019, click on the Network Internet icon on your computer’s home screen and then Network and Internet Settings</p>
<p align="center"><img src="https://i.imgur.com/u5ncidD.png" height="50%" width="50%" alt="image"/>

<p>4. On the Network and Internet page, click on Network and Sharing Center</p>
<p align="center"><img src="https://i.imgur.com/tQr2Z7g.png" height="50%" width="50%" alt="image"/>

<p>5. On the Network and Sharing Center page, click on “Ethernet0” and on the Ethernet0 status page, click on properties. </p>
<p align="center"><img src="https://i.imgur.com/P87QxjV.png" height="50%" width="50%" alt="image"/>
<p align="center"><img src="https://i.imgur.com/az0Ss5R.png" height="50%" width="50%" alt="image"/>

<p>6. .On the Ethernet0 properties’ page, double click on “Internet Protocol Version 4(TCP/IPv4) from the list of items</p>
<p align="center"><img src="https://i.imgur.com/dvw795Y.png" height="50%" width="50%" alt="image"/>

<p>7. On the Internet Protocol version 4(TCP/IPv4) Properties’ page, select the “use the following IP address” and input the desired IP address, subnet mask and DNS server address. Then click OK to save.</p>
<p align="center"><img src="https://i.imgur.com/cfXS3F4.png" height="50%" width="50%" alt="image"/>

<br>
<br>
<br>

<h2>*Change the Name and IP Addresses of the VMs - Windows 11</h2>
<p>1. To change the name of Windows 11 VM, go to file explorer, right click on “This PC” and click on properties. </p>
<p align="center"><img src="https://i.imgur.com/gqBOSsv.png" height="50%" width="50%" alt="image"/>

<p>2. On the system’s settings screen, click on Advanced system settings</p>
<p align="center"><img src="https://i.imgur.com/ppNZtEG.png" height="50%" width="50%" alt="image"/>

<p>3. On the system’s properties’ screen, in the computer name tab, click change.</p>
<p align="center"><img src="https://i.imgur.com/VNTFoN8.png" height="50%" width="50%" alt="image"/>

<p>4. In the computer name/domain changes' page, input the desired name in the space provided for computer name and click OK to save.</p>
<p align="center"><img src="https://i.imgur.com/XaZvK25.png" height="50%" width="50%" alt="image"/>
  
<p>5. To change the IP address of the windows 11 VM, right click on start and click on settings </p>
<p align="center"><img src="https://i.imgur.com/iOQHfcK.png" height="50%" width="50%" alt="image"/>

<p>6. On the settings screen, click on Network and Internet. On the Network and Internet pane, click on Ethernet</p>
<p align="center"><img src="https://i.imgur.com/q4pI3y6.png" height="50%" width="50%" alt="image"/>

<p>7. On the Ethernet pane, under IP assignment, click on Edit</p>
<p align="center"><img src="https://i.imgur.com/dt3N8Cr.png" height="50%" width="50%" alt="image"/>

<p>8. On the Edit IP settings screen, make sure to change it to manual and input the desired IP address and Preferred DNS address. Then click SAVE.</p>
<p align="center"><img src="https://i.imgur.com/uHbJpLD.png" height="50%" width="50%" alt="image"/>

<br>
<br>

<h1>Connect all VMs to the same virtual Network VMware Workstation Pro</h1>
<p>This tutorial outlines how to connect all VMs on the same virtual network for communication.<br /></p>

<P>1. To connect all VMs to the same network, right click on the VM and go to settings</P>
<p align="center"><img src="https://i.imgur.com/Y51MkeN.png" height="50%" width="50%" alt="image"/>

<p>2. On the Virtual machine settings screen, just in the hardware window, click on the Network Adapter and set it to custom. From the dropdown menu, select the desired virtual network and click OK to save. Make sure this is done across all other VMs you wish to put on the same network.</p>
<p align="center"><img src="https://i.imgur.com/Rzo2FXa.png" height="50%" width="50%" alt="image"/>

<br>
