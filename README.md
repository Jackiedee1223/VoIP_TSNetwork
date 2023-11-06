# Hotel Management Network Design & Implementation
<h2>Introduction</h2>
<p>We are required to design and implement Vic Modern Hotel network. The hotel has three floors; in the first floor there three departments (Reception, store and Logistics), in the second floor there are three departments (Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation:</p>

* There should be three routers connecting each floor (all placed in the server room in IT department).<br> 
* All routers should be connected to each other using serial DCE cable.<br> 
* Each floor is expected to have one switch (placed in the respective floor).<br> 
* Each floor is expected to have WIFI networks connected to laptops and phones.<br> 
* Each department is expected to have a printer.<br>
* Each department is expected to be in different VLAN with the following details.<br> 


<h2>Details</h2>

<b>1st Floor</b>
- Reception- VLAN 80, Network of 192.168.8.0/24
- Store- VLAN 70, Network of 192.168.7.0/24
- Logistics- VLAN 60, Network of 192.168.6.0/24

<b>2nd Floor</b>
- Finance- VLAN 50, Network of 192.168.5.0/24
- HR- VLAN 40, Network of 192.168.4.0/24
- Sales- VLAN 30, Network of 192.168.3.0/24

<b>3rd Floor</b>
- Admin- VLAN 20, Network of 192.168.2.0/24
- IT- VLAN 10, Network of 192.168.1.0/24


<h2>Technologies Implemented</h2>

* Use OSPF as the routing protocol to advertise routes.
* All devices in the network are expected to obtain IP address dynamically with their respective router configured as the DHCP server.
* All the devices in the network are expected to communicate with each other.
* Configure SSH in all the routers for remote login.
* In IT department, add PC called Test-PC to port fa0/1 and use it to test remote login.
* Configure port security to IT-dept switch to allow only Test-PC to access port fa0/1 (use sticky method to obtain mac-address with violation mode of shutdown.

<h2>Steps</h2>
<p>1. Creating a network topology.</p>
<p>2. Hierarchical Network Design.</p>
3. Connecting Networking devices with Correct cabling.</p>
4. Creating VLANs and assigning ports VLAN numbers.</p>
5. Subnetting and IP Addressing.</p>
6. Configuring Inter-VLAN Routing (Router on a stick).</p>
7. Configuring DHCP Server (Router as the DHCP Server).</p>
8. Configuring SSH for secure Remote access.</p>
9. Configuring switchport security or Port-Security on the switches.</p>
10. Configuring WLAN or wireless network (Cisco Access Point).</p>
11. Host Device Configurations.</p>
12. Test and Verifying Network Communication.</p>


<h2>Result</h2>
<img src="https://github.com/Jackiedee1223/image-repos/blob/main/hmi.png">

<h2>Reference</h2>
<p>Learning from <b>GURUTECH NETWORKS<br> </p>

