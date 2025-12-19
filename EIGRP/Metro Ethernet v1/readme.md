<img width="1411" height="736" alt="EIGRP Lab" src="https://github.com/user-attachments/assets/5b405722-e6c0-416d-a6c9-ed1830ad7a77" />

Scenario:
This lab demonstrates EIGRP connectivity between one office site in the Dallas to a smaller branch office site, Frisco, there in the metro. 
The two sites are connected via a metro ethernet circuit. Both networks exist in AS 100. The core switch pair in dallas serves as l3 
gateways for vlans 10, 20, and 90 using hsrp. 1a serves as primary for vlans 10 and 20 and 1b is primary for vlan 90. Dallas user access 
switches also have an ip configured for svi vlan 10 for reachability and troubleshooting purposes, other than that they are purly just l2 switches.

The Frisco site is small, single threaded site. The user access switch serves as l3 gateways for vlans 10, 20, and 90 just like the dallas site's core switches. 
Except here there is no redundnacny availiable since this a low severity site legacy site that is planned for decomission.
