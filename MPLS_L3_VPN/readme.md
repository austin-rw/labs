I decided I wanted to simulate an mpls network and connect two small branch offices that are in the same OSPF area. Although 'Area 0' is shown here, it does not serve as
the customer's backbone, it mainly for the mpls core network that the customer doesnt manage. Below are more details about the lab:

- MPLS network is configured with OSPF 'Area 0' as its internal area network. It is also using internal BGP peering between PE-1 and PE-2 in a MP-BGP setup using LDP and VPNv4
- vrf 'COMPANY-A' is used within the mpls network to label customer-a traffic. I used a simple rd '1:1' to distinguish the route.
- Both office sites have a 'Data' VLAN 10. I mainly made this to validate end to end user connectivity between the two sites. As seen in the screen shot that shows the ping results and routes.

please feel free to take a look at the configs or download the lab file and import it into cml

<img width="1223" height="1271" alt="2025-12-20 17_23_36-" src="https://github.com/user-attachments/assets/0eada1bc-c0c2-4c51-bdf6-2ec7ecc1db47" />

