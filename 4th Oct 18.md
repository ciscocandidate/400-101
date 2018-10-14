## Q1 
Which two options are valid IPv6 extension header types? (Choose two) 
  
A.Mobility    
B.Encapsulating Security Payload    
C.Version    
D.Flow Label    
E.Traffic Class  


Answer:  A, B 

---

## Q2 
Refer to the exhibit. Which three statements correctly describe the route reflector's behavior? (Choose two.)  
![exhibit][q2]
  
A.The route reflector will not reflect routes from R3 to R1    
B.The route reflector will reflect routes from R3 to R1    
C.The route reflector will not reflect routes from R1 to R3    
D.The route reflector will reflect routes from R1 to R2    
E.The route reflector will reflect routes from R1 to R3    
F.The route reflector will not reflect routes from R1 to R2  


Answer:  B E F 

---


## Q3 
Which two operating modes does VPLS support, (choose two). 
  
A.dynamic mode    
B.transport mode    
C.strict mode    
D.port mode    
E.VLAN mode    
F.loose mode  

Answer:  D E 

---

## Q4 
What command can you enter on a Cisco router so that it can both poll a time server and be polled by a time server? 
  
A.ntp server    
B.ntp broadcast destination    
C.ntp peer    
D.ntp broadcast client  

Answer:  A

---

## Q5 
Which option describes how a router responds if LSA throttling is configured and it receives the identical LSA before the interval is set? 
  
A.The LSA is ignored    
B.The LSA is ignored and a notification is sent to the sending router to slow down its LSA packet updates    
C.The LSA is added to the OSPF database    
D.The LSA is added to the OSPF database and a notification is sent to the sending router to slow down its LSA packet updates  

Answer:  A 

---

## Q6 
![exhibit][q6]  
R1 is performing mutual redistribution, but OSPF routes from R3 are unable to reach R2. Which three options are possible reasons for this behavior? (Choose three.) 
  
A.R1 requires a seed metric to redistribute RIP.    
B.The RIP version supports only classful subnet masks.    
C.R1 is filtering OSPF routes when redistributing into RIP.    
D.R3 and R1 have the same router    
E.R1 and R3 have an MTU mismatch.    
F.R2 is configured to offset OSPF routes with a metric of 16.  

Answer:  A, C, F 

---

## Q7 
Which statement about EIGRP request packets is true? 
  
A.They determine whether a destination is reachable    
B.They are transmitted unreliably    
C.They are transmitted via broadcast    
D.They are sent in response to queries  

Answer:  B  

---

## Q8 
Which two statements about the passive-interface command issued under EIGRP are true? (Choose two) 
  
A.It configures the interface to use unicast messages to establish EIGRP neighbor relationships    
B.It allows incoming routing updates to be received but disables outgoing routing updates    
C.It disables processing of incoming hello messages    
D.It configures the device to advertise only connected Interfaces to neighbors with EIGRP    
E.If it is enabled globally under EIGRP on the device, it can be disabled for individual interfaces to allow those interfaces to remain active 

Answer:  C, E  

---

## Q9 
Which statement about the BGP scope of the cost community is true? 
  
A.It is shared with IBGP neighbors only.    
B.It is shared with EBGP neighbors only.    
C.It is shared with IBGP and confederation peers.    
D.It is shared with IBGP and EBGP neighbors.    
E.It is shared with IBGP neighbors and route reflectors.   

Answer:  C  

---

## Q10
Drag and drop each IPv6 tunnel type from the left onto the matching description on the right.  
![exhibit][q10]

Answer: 6to4 6RD ISATAP IPv4-compatable GRE Manual 

---

## Q11
A cloud service provider is designing a large multitenant data center to support thousands of tenants. The provider is connected about the scalability of the Layer 2 network and providing Layer 2 segmentation to potentially thousands of tenants. Which Layer 2 technology is best suited in this scenario? 
  
A.Extended VLAN ranges    
B.LDP    
C.VRF    
D.VXLAN  

Answer:  D

---

## Q12 
Refer to the exhibit. Which statement about the R1 configuration is true?  
![exhibit][q12]
  
A.It permits host 10.1.1.2 to establish a Telnet connection to R1.    
B.It limits remote hosts to two SSH connection attempts.    
C.SSH connections to R1 will log out after a 5-minute idle interval.    
D.Hosts that reside on network 10.0.0.0/8 can SSH to R1.    
E.The R1 timeout for outgoing SSH connection attempts is 30 seconds.  

Answer:  E 

---

## Q13
Which IEE wireless standard is predominantly used for smart object for communication?
  
A.802.11    
B.802.22    
C.802.15.1    
D.802.15.4  

Answer:  D 

---

## Q14
What are two features that distance-vector routing protocols can use to address the count-to-infinity 
problem? (Choose two.) 
  
A.triggered updates    
B.route poisoning    
C.split horizon    
D.route tagging    
E.adjacency dead timers  

Answer:  B, C 

---

## Q15
Which statement about PMTUD is true? 
  
A.It is supported by TCP and UDP.    
B.GRE tunnels use PMTUD to fragment data packets by default.    
C.It is used to prevent fragmentation of packets at the endpoint of a TCP connection.    
D.It is used to prevent fragmentation of packets traveling across a smaller MTU link between two endpoints.    
E.It increases the connection's send MSS value to prevent fragmentation.  

Answer:  A  

---

## Q16 
Refer to the exhibit. Which option is the state of the OSPF adjacency between routers R1 and R2? 
![exhibit][q16]
  
A.EXCHANGE    
B.LOADING    
C.ATTEMPT    
D.2 WAY    
E.FULL 

Answer:  A  
URL: https://networklessons.com/ospf/ospf-packets-and-neighbor-discovery/

---

## Q17 
Refer to the exhibit. To which undesirable condition can router R1 be vulnerable? 
![exhibit][q17]
  
A.Denial of service attacks    
B.Unicast flooding    
C.Man-in-the-middle attacks    
D.Asymmetric routing    
E.IP address spoofing   

Answer:  A  
URL: http://www.ciscopress.com/articles/article.asp?p=345618&seqNum=5

---

## Q18 
Drag each OSPFv2 SA parameter on the left to its, corresponding description on the right  
![exhibit][q18]

Answer: KeyID Key Start generate Key Stop Accept Authentication key Key Stop Generate Authentication Algorithm Start Accept 

---

## Q19 
How many address families can a single 0SPFv3 instance support? 
  
A.5    
B.2    
C.1    
D.10  

Answer:  C   

---

## Q20 
Which condition must be true to allow an access port to trust QoS markings on an incoming frame? 
  
A.The switch must be configured globally with the mls qos trust cos command.    
B.The port must be configured with the mls qos cos command.    
C.The port must be configured with the mls qos trust dscp command.    
D.The switch must be configured globally with the vlan dot1q tag native command.

Answer:  C   

---

## Q21 
Refer to the exhibit. Which two statements about the output are true? (Choose two.)  
![exhibit][q21]

A.This switch is the root bridge for VLAN 1    
B.Setting the priority of this switch to 0 for VLAN 1 would cause it to become the new root.    
C.Spanning-tree PortFast should not be enabled on GigabitEthernet2/1    
D.Spanning tree PortFast is enabled on GigabitEthernetl/1    
E.802.1 w spanning tree is being used  

Answer:  B, C  

---

## Q22
Which router on an IS-IS network generates the IS-IS pseudonode?
  
A.DIS    
B.Level 1/ Level 2 Router    
C.ABR    
D.ASBR  

Answer:  A  
URL: https://www.cisco.com/c/en/us/support/docs/ip/integrated-intermediate-system-to-intermediate-system-is-is/49627-DIS-LSP-1.html

---

## Q23
Refer to the exhibit, which two options are problems that can occur with this configuration? (Choose two)  
![exhibit][q23]
  
A.The label for the R5 loopback address is filtered from other MPLS routers    
B.MPLS traffic from R1 to R5 takes a suboptimal path    
C.The MPLS path from R1 to R5 becomes unreachable    
D.The label for the R1 loopback address is filtered from MPLS routers    
E.R1 and R5 are unable to establish an LDP relationship  

Answer:  A, C 

---

## Q24
Which configuration can you implement on PE-1 to allow CE-1 to receive delegated IPv6 prefixes
  
A.   
![exhibit][q24a]  
B.  
![exhibit][q24b]  
C.  
![exhibit][q24c]  
D.  
![exhibit][q24d]  

Answer:  A  

---

## Q25
When is it useful to disable split horizon on an EIGRP interface?
  
A.It is never advisable to disable split horizon on an EIGRP interface    
B.Disable it when you want to send routes that are learned from another routing protocol to peers on the same interface    
C.Disable it when you need to send updates to peers on the interface on which the updates were received    
D.Disable it when you want to provide additional backup paths in your network  

Answer:  C 

---

## Q26
Which three statements are true about PPP CHAP authentication? (Choose three.) 
  
A.The LCP phase must be complete and in closed state.    
B.PPP encapsulation must be enabled globally.    
C.By default, the router uses it hostname to identify itself to the peer.    
D.The hostname used by a router for CHAP authentication cannot be changed.    
E.The LCP phase must be complete and in open state.    
F.PPP encapsulation must be enabled on the interface. 

Answer:  C, E, F 

---

## Q27
Which IPv6 tunneling mechanism requires a service provider to use one of its own native IPv6 blocks to guarantee that its IPv6 hosts will be reachable? 
  
A.automatic 4to6 tunneling    
B.NAT-PT tunneling    
C.ISATAP tunneling    
D.6rd tunneling    
E.automatic 6to4 tunneling    
F.manual ipv6ip tunneling  

Answer:  D 

---

## Q28
Which two statements about EIGRP wide metrics are true? (Chose two)
  
A.It requires named configuration    
B.It supports interface bandwidth up to 10 terabits per second    
C.It supports interface bandwidth up to 4.2 terabits per second    
D.It is supported in both named mode configuration and classic mode    
E.It uses a 21-bit metric calculation  

Answer:  A, C 

---

## Q29
Which statement about a type 4 LSA in OSPF is true?
  
A.It is an LSA that is originated by an ABR, that is flooded throughout the AS, and that describes a route to the ABR.    
B.It is an LSA that is originated by an ASBR, that is flooded throughout the area, and that describes a route to ASBR    
C.It is an LSA that is originated by an ASBR, that is flooded throughout the AS, and that describes a route to the ASBR     
D.It is an LSA that is originated by an ABR, that is flooded throughout the AS, and that describes a route to the ASBR    
E.It is an LSA that is originated by an ABR, that is flooded throughout the area, and that describes a route to the ASBR  

Answer:  E 

---

## Q30
You are backing up a server with a 1 Gbps link and a latency of 2 ms. Which two statements about the backup are true? (Choose two.) 
  
A.The bandwidth delay product is 50Mb.    
B.The bandwidth delay product is 2Mb.    
C.The default TCP receive window size is the limiting factor.    
D.The bandwidth delay product is 500 Mb.    
E.The default TCP send window size is the limiting factor.  

Answer:  B, C 

---

## Q31 
Refer to the exhibit. Which EIGRP routes will appear in the routing table of R2 ?  
![exhibit][q31]
  
A.2001:12::1/64    
B.2001:12::1/128    
C.2001:112::/64,2001:12::1/64    
D.2001:112::/64,2001:12::1/128  

Answer:  B

---

## Q32
In which way does the Bridge Assurance mechanism modify the default spanning tree behavior in an effort to prevent bridging loops? 
  
A.Received BPDUs are looped back toward the sender to ensure that the link is bidirectional.    
B.If BPDUs are no longer received on a port, the switch immediately sends out a TCN BPDU.    
C.Extended topology information is encoded into all BPDUs.    
D.BPDUs are sent bidirectional on all active network ports, including blocked and alternate ports. 

Answer:  D 

---

## Q33
Refer to the exhibit. After you apply the given configurations to R1 and R2. Which networks does R2 advertise to R1?  
![exhibit][q33]
  
A.172.16.0.0/16 only    
B.Both 172.16.32.0/20 and 172.16.33.0/24    
C.172.16.32.0/20 only    
D.172.16.33.0/24 only  

Answer:  A 

---

## Q34 
Which two statements about PPP PAP are true? (Choose two.) 
  
A.It can protect against playback attacks.   
B.It is vulnerable to trial-and-error attacks.   
C.It requires two-way authentication.   
D.It is supported only on synchronous interfaces.   
E.Login attempts are controlled by the remote node.

Answer:  B, E 

---

## Q35 
Which options lists the cloud service models?
  
A.Infrastructure as a service, Platform as a service, and storage and storage as a service   
B.Infrastructure as a service, Platform as a service, and storage and software as a service   
C.Internet as a service, Platform as a service, and storage as a service   
D.Internet as a service, Product as a service, and storage as a service   
E.Infrastrucutre as a service, Platform as a service, and software as a service

Answer:  E

---

## Q36 
Refer to the exhibit. Which effect of this configuration is true?  
![exhibit][q36]
  
A.It configures a PPPoE server   
B.It configures a PPPoE neighbor relationship with a Layer 3 switch   
C.It configures a PPPoE client   
D.It configures a PPPoE session with an ISP 

Answer:  A 

---

## Q37 
What are the two major requirements for configuring an extended VLAN with VTPv2? (Choose two)
  
A.The reduced MAC address feature must be disabled   
B.VLAN pruning must be enabled   
C.The VLAN must be configured in VLAN database mode   
D.The configuration must be in global configuration mode   
E.The device must be operating in VTP transparent mode

Answer:  D, E 

---

## Q38 
Which two options are restrictions of BGP Outbound Route Filtering? (Choose two)
  
A.It can be used only with eBGP   
B.Multicast is not supported   
C.It can be used only with IPv4 multicast   
D.It requires access list to match to routes   
E.I can be used only with iBGP

Answer:  A, B 

---

## Q39 
When you implement redistribution on your network, which feature can you enable to prevent suboptimal routing?
  
A.route tagging   
B.authentication   
C.VRFs   
D.NBAR 

Answer:  A 

---

## Q40
Refer to the exhibit, how can you configure R6 so that traffic returns to subnet 172.16.6.0/24 via R5?  
![exhibit][q40]
  
A.Configure the neighbor 10.5.6.5 send-community standard command   
B.Advertise prefix 172.16.6.0/24 to neighbor R5 with metric 80   
C.Set the local preference for all prefixes received from neighbor R5 to 200   
D.Advertise prefix 172.16.6.0/24 to neighbor R5 with AS 65006 prepended.

Answer:  A 

---

## Q41 
What is a requirement for BFD static route support? 
  
A.All routers that will carry traffic must be the same model.   
B.All routers that will carry traffic must have the same software version.   
C.BFD must be configured on all Ethernet, virtual-template, and dialer interfaces that will carry traffic.   
D.CEF must be configured on all routers that will carry traffic.

Answer:  D 

---

## Q42 
Which two statements about PIM-DM are true? (Choose two) 
  
A.It requires an RP   
B.It forwards multicast packets to neighbors that have required the data   
C.It forwards multicast packets on a shared distribution tree   
D.It forwards multicast packets on a source tree   
E.It floods multicast packets to neighbors that have requested the data   
F.It floods multicast packets throughout the network

Answer:  D, F 

---

## Q43 
Refer to the exhibit. If you apply this configuration to a device on your network, which class map cannot match traffic?  
![exhibit][q43]
  
A.CM-EXAMPLE-2   
B.CM-EXAMPLE-1   
C.CM-EXAMPLE-5   
D.CM-EXAMPLE-3   
E.CM-EXAMPLE-4

Answer:  D

---

## Q44 
Which two statements are true about IS-IS? (Choose two.) 
  
A.IS-IS SPF calculation is performed in three phases.   
B.IS-IS can never be routed beyond the immediate next hop.   
C.IS-IS works over the data link layer, which does not provide for fragmentation and reassembly.   
D.IS-IS DIS election is nondeterministic. 

Answer:  B, C 

---

## Q45 
A user is presented with the underlying hardware and software needed to develop and offer applications via the internet from a cloud service provider. Which cloud model is this user consuming?
  
A.Application as a service   
B.Software as a service   
C.Platform as a service   
D.Infrastructure as a service

Answer:  C 

---

## Q46
Refer to the exhibit. Which additional configuration statement is required on R3 in order to allow multicast traffic sourced from 192.168.13.3 to flow along the shared-tree?  
![exhibit][q46]
  
A.ip mroute 10.4.4.4 255.255.255.255 Tunnel 0   
B.ip route 10.4.4.4 255.255.255.255 Tunnel 0   
C.ip route 192.168.14.0 255.255.255.0 Tunnel 0   
D.ip mroute 192.168.14.0 255.255.255.0 Tunnel 0

Answer:  A 

---

## Q47 
Which statement about Control Plane Policing is true?
  
A.It applies to packets that are punted to the route processor   
B.It queues egress packets that would otherwise be discarded   
C.It queues ingress packets that would otherwise be discarded   
D.It applies to packets that are generated locally

Answer:  A 

---

## Q48 
Which two statements about VPLS are true? (Choose two.) 
  
A.Split horizon is used on PE devices to prevent loops.   
B.Spanning tree is extended from CE to PE  
C.IP is used to switch Ethernet frames between sites.   
D.PE routers dynamically associate to peers.   
E.VPLS extends a Layer 2 broadcast domain. 

Answer:  A, E 

---

## Q49 
Which two options are 802.15.4 node types? (Choose two)
  
A.Limited Function Device   
B.Reduced Function Device   
C.Expanded Function Device   
D.Mesh Function Device   
E.Full Function Device

Answer:  B, E 

---

## Q50 
Which two statements about IPv6 RA guard are true?
  
A.It is applied only on the egress interface   
B.It is applied only on the ingress interface   
C.It can be applied on ingress and egress interfaces   
D.It must be applied individually to specific interfaces   
E.It can be applied globally to all interfaces on the device   
F.It supports global polices that match an ACL based on the source IP address

Answer:  B, F

---

## Q51 
Which way to influence path selection with EIGRP is preferred? 
  
A.changing the delay, even if it must be done on multiple in1erfaces   
B.changing the bandwidth, because that is wha1 Cisco recommends   
C.changing the bandwidth, because it does not have any impact on o1her router fea1ures   
D.changing the bandwidth, because it must be done only on one interface along the path 

Answer:  A  

---

## Q52 
Which technology, implemented on aggregation-edge nodes at the aggregation layer, provides per-tenant isolation at Layer 3, with separate dedicated per-tenant routing and forwarding tables on the inside interfaces of firewall context?
  
A.VRF-Lite   
B.VLAN   
C.VDC   
D.VXLAN

Answer:  A

---

## Q53 
Which three values are used to generate a unique bridge ID for each VLAN in PVST+? (Choose three.) 
  
A.port cost   
B.spanning-tree MAC address   
C.port priority   
D.max age   
E.extended system ID   
F.switch priority

Answer:  B, E, F 

---

## Q54 
Which aspect is a significant disadvantage of containers?
  
A.Security   
B.Resource consumption   
C.Time to delay   
D.Inefficiency   
E.Reduce operational overhead

Answer:  A 

---

## Q55 
Drag and drop each IPv6 address type from the left onto the correct link-local multicast address on the right  
![exhibit][q55]

Answer:  
![exhibit][q55a]

---

## Q56 
Drag each IPv4 host address on the left to the matching broadcast address on the right  
![exhibit][q56]

Answer: 1:3 2:1 3:2 4:6 5:5 6:3 

---

## Q57 
What are the two EEM event subscribers? (Choose two) 
  
A.applet   
B.script   
C.syslog   
D.CLI   
E.none 

Answer:  A, B 

---

## Q58 
What is a major disadvantage of virtual machines versus containers?
  
A.Boot time   
B.Security   
C.Operational Management   
D.Limited management tools   
E.Vendor lock-in

Answer:  B 

---

## Q59 
Which three technologies can be used to implement redundancy for IPv6? (Choose three.) 
  
A.NHRP   
B.DVMRP   
C.HSRP   
D.GLBP   
E.IPv6 NA   
F.IPv6 RA

Answer:  C, D, F 

---

## Q60 
Which IPv6 first-hop security feature blocks traffic sourced from IPv6 addresses that are outside the prefix gleaned from router advertisements? 
  
A.IPv6 source guard.   
B.IPv6 RA guard.   
C.IPv6 prefix guard.   
D.IPv6 DHCP guard.

Answer:  C 

---

## Q61 
Company A has two remote sites, which are connected to a common ISP by BGP. At each site, Company A is using the same autonomous system number. Which BGP feature can you implement to enable routing between the two sites? 
  
A.communities   
B.allowas-in   
C.AS path prepending   
D.Peer groups

Answer:  B 

---

## Q62 
Which prefix list matches and permits all RFC 1918 network 10.0.0.0 routes that have masks of /16 through /24? 
  
A.ip prefix-list foo seq 10 permit 10.0.0.0/16 ge 15 le 25   
B.ip prefix-list foo seq 10 permit 10.0.0.0/8 ge 15 le 25   
C.ip prefix-list foo seq 10 permit 10.0.0.0/8 ge 16 le 24   
D.ip prefix-list foo seq 10 permit 10.0.0.0/16 le 24 

Answer:  C 

---

## Q63 
Drag and drop the BGP feature on the left to the corresponding function it performs on the right  
![exhibit][q63]

Answer: 1-A, 2-D, 3-E, 4-B, 5-C 

---

## Q64 
Which three terms are used to describe an OS-level virtualization method for deploying and running distributed applications? (Choose three)
  
A.Containerization   
B.Container networking   
C.Container-based virtualization   
D.Virtualized networking   
E.Application containerization   
F.Container Stack  
G.Shared Kernel

Answer:  A, C, E 

---

## Q65 
Which two statements about GETVPN are true? (Choose two)
  
A.It supports non-IP protocols   
B.It is supported on MPLS networks   
C.It uses stateless failover for high availability   
D.It can use GRE or DMVPN to support private IP addressing   
E.It supports only hub-spoke topologies

Answer:  B, C 

---

## Q66 
Which value does EIGRP use to determine the metric for a summary address? 
  
A.The average of the component metrics   
B.The highest metric among the component routes   
C.A default fixed value   
D.The lowest metric among the component routes 

Answer:  D 

---

## Q67 
Which value is the maximum segment size if you start with an MTU of 1500 bytes and then remove the overhead of the Ethernet header, IP header, TCP header, and the MAC frame check sequence? 
  
A.1434 bytes   
B.1460 bytes   
C.1458 bytes   
D.1464 bytes  

Answer:  B 

---

## Q68 
Which statement is true about a valid IPv6 address that can be configured on tunnel interface0? 
  
A.There is not enough information to calculate the IPv6 address.   
B.6to4 tunneling allows you to use any IPv6 address.   
C.2001:7DCB:5901::/128 is a valid IPv6 address.   
D.2002:7DCB:5901::/128 is a valid IPv6 address.  

Answer:  D 

---

## Q69 
Which two methods do IPsec VTIs used to identify and transmit encrypted traffic through the tunnel? (Choose two) 
  
A.static routing   
B.dynamic routing   
C.object groups   
D.ACLs   
E.NAT

Answer:  A, B 

---

## Q70 
Which two statements about VTPv3 are true? (Choose two)
  
A.Extended VLANs prevent VTPv3 switches from becoming VTPv2   
B.VTPv3 must receive VTPv2 packets before it can send VTPv2 packets   
C.VTPv3 accepts configuration information only from VTPv2 devices   
D.VTPv3 sends VTPv2 packets when they are detected on a trunk port   
E.VTPv3 regions can communicate in server mode only over a VTPv2 region

Answer:  A, B  

---

## Q71 
Drag and drop each statement about LISP devices from the left onto the correct LSIP device type on the right.  
![exhibit][q71]

Answer:  
![exhibit][q71a]

---

## Q72 
How dose having an EIGRP feasible successor speed up convergence? 
  
A.EIGRP sends quires only if there is a feasible successor, which decreases the number of routers that are involved in convergence.   
B.EIGRP immediately installs the loop-free alternatives path in the RIB   
C.EIGRP preinstalls the feasible successor in the RIB in all cases which traffic to switch more quickly   
D.EIGRP sends queries only if there is not a feasible successor which causes less control traffic to complete with data

Answer:  B 

---

## Q73 
Drag and drop the OSPF network type on the left to the correct category of timers on the right  
![exhibit][q73]

Answer:   
![exhibit][q73a]

---

## Q74 
How does MSTP maintain compatibility with RSTP? 
  
A.RSTP encodes region information from an MSTP BPDU into a single instance.   
B.MSTP supports five port states in the same way as RSTP.   
C.MSTP sends all spanning-tree information in one BPDU.   
D.RSTP implements a TTL that is compatible with the MSTP max age timer  

Answer:  C

---

## Q75 
When is it most important to implement multiple synonymous area addresses on an IS-IS network? 
  
A.when integrating an IS-IS Layer 2 router with another routing protocol   
B.when merging or splitting areas in the IS-IS domain   
C.when an IS-IS router is merging routing information   
D.when splitting areas in the IS-IS domain  

Answer:  B

---

## Q78
Which option is a core event publisher for EEM? 
  
A.Policy Director  
B.Timer  
C.Script  
D.Applet 

Answer:  B

---

## Q79
Which two options are interface requirements for turbo flooding? (Choose two.) 
  
A.The interface is Ethernet.  
B.The interface is configured for ARPA encapsulation.  
C.The interface is PPP.  
D.The interface is configured for GRE encapsulation.  
E.The interface is configured for 802.1Q encapsulation. 

Answer:  A, B

---

## Q80 
Refer to the exhibit. Which configuration must you apply to a router so that it can generate a log message in this format?  
![exhibit][q80]
  
A.  
service timestamps log datetime msec localtime  
service sequence-numbers   
B.  
service timestamps log datetime msec localtime show-timezone   
service alignment logging   
C.  
service timestamps log datetime msec localtime show-timezone  
service sequence-numbers   
D.  
service timestamps log datetime localtime show-timezone  
service sequence-numbers  
E.  
service timestamps log datetimemsec localtime show-timezone  
service linenumber

Answer:  C

---

## Q81 
Which statement about Auto-RP is true? 
  
A.All interfaces must be configured in dense mode  
B.All interfaces must be configured in sparse-dense mode.  
C.All interfaces must be configured in sparse mode.  
D.An RP that it tied to a loopback address must be configured 

Answer:  D

---

## Q82 
Which statement about the EIGRP SRTT is true?
  
A.It is the time that it takes to receive a reply to a query   
B.It is six times the RTO   
C.It is the average time that it takes for a reliable packet to be acknowledged   
D.It is the time that it takes for an update to be received by a peer

Answer:  C 

---

## Q83 
Which two statements about scheduling multiple IP SLA operations are true? (Choose two)
  
A.The IP SLA monitor group schedule command must be configured on the device   
B.The IP SLA operations must be scheduled at a minimum interval of 30 seconds   
C.You must configure the frequency of each IP SLA operation before it can start   
D.Every IP SLA operation in a single group must start at the same time   
E.You must configure IP SLA operations before you can schedule a group of operations

Answer:  A, E 

---

## Q84 
Which three options are three of the valid message types for DHCPv6 ? (Choose Three) 
  
A.Discover  
B.Solicit  
C.Request  
D.Leave  
E.Offer  
F.Advertise 

Answer:  B, C, F 

---

## Q85 
In which scenario can you host the most instances on a server?
  
A.Using virtual machines in containers   
B.Using containers in virtual machines   
C.Using microservices application   
D.Using on containers   
E.Using only virtual machines

Answer:  D 

---

## Q86
Which feature prevents the formation of inter area routing loops? 
  
A.the backbone area   
B.stub areas   
C.redistribution   
D.shortest-path trees

Answer:  A

---

## Q87
Which two OSPF network types require the use of a DR and BDR? (Choose two.) 
  
A.non-broadcast networks  
B.point-to-point networks  
C.point-to-multipoint networks  
D.broadcast networks  
E.point-to-multipoint non-broadcast networks 

Answer:  A, D

---

## Q88 
Which two statements about DMVPN are true? 
  
A.It is a tunnel-less VPN technology  
B.It supports multicast and QoS within tunnels  
C.It provides a routetable interface for terminating IPsec tunnels  
D.It uses automatic IPsec triggering to build IPsec tunnels  
E.It allows both the hub and the spokes to use dynamic IP address  
F.It is an open standard 

Answer:  B, D

---

## Q89
Refer to the exhibit. After observing that an OSPF neighbor relationship failed to form, you executed a debug that returned the given output. Which configuration issue prevented the OSPF neighbor relationship from Forming?  
![exhibit][q89]
  
A.The hello and hold timers are mismatched.   
B.The area IDs are mismatched   
C.The devices are on different subnets.   
D.The Stub flag is set on the neighboring device.

Answer:  C  

---

## Q90
Which three management protocols does MPP support? (Choose three.) 
  
A.SSH   
B.SMTP   
C.NetFlow   
D.Telnet   
E.SCP   
F.SNMP

Answer:  A, D, F 

---

## Q91
Which two statements about native VLANs are true? (Choose two) 
  
A.They are used to forward untagged traffic only   
B.They are used to forward both tagged and untagged traffic.   
C.They are configured in VL.AN database mode   
D.They are used to forward tagged traffic only.   
E.They are configured under the trunk interface   
F.They require VTPv3

Answer:  AE 

---

## Q92 
You are configuring a DMVPN hub to perform CBWFQ on a per-spoke basis. Which information is used to identify the spoke? 
  
A.the NHRP network ID  
B.the spoke tunnel source IP  
C.the spoke tunnel interface IP address  
D.the NHRP group 

Answer:  D

---

## Q93 
Which three options are capabilities of queuing and scheduling? (Choose three) 
  
A.PBR   
B.CAR   
C.bandwidth limitation   
D.queue buffers   
E.weighted tail drop   
F.policing

Answer:  C, D, E

---

## Q94
What are two pieces of information that can be transmitted via Multiprotocol BGP? (Choose two)
  
A.Level 2 routes set the attached bit   
B.MPLS VPN routes   
C.Multicast sources   
D.IS-IS LSAs   
E.Level 1/level 2 routers set the overload bit   
F.OSPF routes

Answer:  B, C 

---

## Q95
For which feature is the address family "rtfilter" used? 
  
A.Enhanced Route Refresh  
B.MPLS VPN filtering  
C.Route Target Constraint  
D.Unified MPLS 

Answer:  C

---

## Q96
Which two authentication options were new in SNMPv3? (Choose two.) 
  
A.noAuth   
B.authPriv   
C.Priv   
D.Auth   
E.authNoPriv   
F.noAuthNoPriv

Answer:  B, E

---

## Q97
What are two differences between IPv6 ISATAP tunneling and IPv6 6to4 tunneling? (Choose two)
  
A.Only ISATAP tunneling can transfer IPv6 multicast packets   
B.Only 6to4 tunneling transfers unicast IPv6 packets within a site   
C.Only ISATAP tunneling transfers unicast IPv6 packets between sites   
D.Only ISATAP tunneling transfers unicast IPv6 packets within a site   
E.Only 6to4 tunneling requires 2002::/16 addresses

Answer:  D, E  

---

## Q99
Which two statements about MSDP are true? (Choose two) 
  
A.It requires multicast sources to be in the same domain.   
B.It uses 32-bit anycast RP addresses.   
C.It uses loopback interfaces for anycast RP addresses.   
D.It uses UDP to establish peering sessions.   
E.All MSDP domains on a given network can share a common RP.   
F.It requires multicast receivers to be in the same domain.

Answer:  A, E 

---

## Q100
Which routing protocol type prevents routing loops by recording each autonomous system that a route traverses?
  
A.Path-vector routing   
B.Link-state routing   
C.Distance-vector routing   
D.Hybrid routing

Answer:  A

---

## Q101
If you configure the set ip default next-hop command on a device and the device receives a packet whose destination is missing from the routing table, how does the device route the packet?
  
A.The packet is policy routed   
B.The packet is policy routed to the destination address in the routing table that is closed to the destination address in the packet   
C.The packet is dropped   
D.The packet is forwarded using the normal routing table

Answer:  A 

---

## Q102
Which two statements about 802.1x authentications with EAP are true? (Choose two)
  
A.The supplicant and authenticator server send a one-time password to the authenticator   
B.The authenticator server translates frames from the supplicant into a RADIUS message   
C.The authenticator can cache the username and password from the authentication server to reduce traffic   
D.The interface passes only EAPOL traffic until the client is authenticated   
E.It uses EAPOL frames between the supplicant and the authenticator

Answer:  B, E 

---

## Q103
Which two statements about STP are true? (Choose two)
  
A.To support load-balancing across redundant paths, the VAN-to-instance mapping must match on all switches in each path   
B.MST configurations are propagated throughout the VTP domain   
C.Only one version of STP can be active on a device at one time   
D.Rapid PVST+ and MST can be active on a device simultaneously   
E.MST supports up to four MST instances, including instance 0

Answer:  A C 

---

## Q104
Which option describes how a VTPv3 device responds when it detects a VTPv2 device on a trunk port?
  
A.It sends a special packet that contains VTPv3 and VTPv2 packet information   
B.It sends VTPv2 packets only   
C.It sends VTPv3 and VTPv2 packets   
D.It sends VTPv3 packets only

Answer:  C

---

## Q105
Which are three basic elements of Cisco Performance Monitor? (Choose three)
  
A.Master controller   
B.SLA   
C.Flow record   
D.Border router   
E.Policy   
F.Class

Answer:  C E F 

---

## Q106
Which two statements about route redistribution are true? (Choose two) 
  
A.Redistributing the entire BGP table from the internet works well using multiple OSPF areas   
B.IS-IS does not support Layer 2 routes that leak into a Layer 1 domain   
C.Mutual redistribution at multiple points can create a routing loop   
D.IBGP is used within the AS to carry EBGP attributes that otherwise would be lost if EBGP was redistributed into IGP.   
E.The unequal cost multipath load-balancing characteristic is lost when redistributing OSPF into EIGRP

Answer:  C, D 

---

## Q107 
Refer to the exhibit. Refer to the exhibit, assuming that all devices are running CDP in default configuration, which of them appear in the R1 show cdp neighbors table?  
![exhibit][q107]
  
A.Router 2, Router 3, Router 5 and Switch A only   
B.Router 2, Router 3, Router 4 and router 5 only   
C.Router 2, and Switch A only   
D.Router 3 and Router 5 only 

Answer:  A 

---

## Q108 
Refer to the exhibit. What will happen to the 10.100.100.0/24 BGP route when the bgp nexthop route-map command is applied as shown?  
![exhibit][q108]
  
A.The route will fall back from iBGP to eBGP   
B.The route will be removed from the routing table   
C.The route will remain unhanged   
D.The route will no longer advertise a next-hop attribute

Answer:  C  

---

## Q109
Drag and drop the set commands from the left into the order in which they are evaluated in a route-map for policy-based routing on the right  
![exhibit][q109]

Answer: A: 2, B:1, C:4, D:3

---

## Q110 
Refer to the exhibit. What are two effects of the given configuration? (Choose two)  
![exhibit][q110]
  
A.The router will manually summarize the 192.168.12.0/27 network   
B.Auto-summarization will be enabled on the F0/0/ interface   
C.The router will fail to form neighbor adjacencies over interface F0/0   
D.The router will fail to form neighbor adjacencies all EIGRP interfaces except F0/0   
E.The router will install the 192.168.12.0/27 network into its EIGRP topology table.

Answer:  C, E 

---

## Q111
Which two statements about WRED are true? (Choose two)
  
A.It is a congestion-avoidance mechanism   
B.It is a packet-classification mechanism   
C.It is a congestion-management mechanism   
D.It drops IP traffic before non-IP traffic   
E.It can be configured on the same interface as WFQ   
F.It is most useful with adaptive traffic

Answer:  A, F 

---

## Q112
Which EIGRP feature allows the use of leak maps?
  
A.Stub   
B.Neighbor   
C.Offset-list   
D.Address-family

Answer:  A

---

## Q113 
Refer to the exhibit. Which router on the given network generates the IS-IS pseudocode?
![exhibit][q113]  

A.R1   
B.R4   
C.R2   
D.R3 

Answer:  A 

---

## Q114
If router R1 is running two OSPF processes, A and B, how can you configure 1 to prefer the A internal routes over the B internal routes?
  
A.Configure the preferred OSPF process with a lower router ID   
B.Change the administrative distance of one of the OSPF process   
C.Change the OSPF cost for the interfaces assigned to one of the OSPF processes   
D.Mutually redistribute the OSPF process into one another   
E.Configure the preferred OSPF process with a higher router ID

Answer:  B 

---

## Q115 
Refer to the exhibit. The OSPF adjacency between two routers cannot be established. What is the root cause of the problem?  
![exhibit][q115]
  
A.Area type mismatch   
B.Authentication error   
C.Mismatched OSPF network types   
D.Different area ID   
E.Both routers are designated routers. 

Answer:  A 

---

## Q116
Refer to the exhibit. What type of IS-IS is configured on R1?  
![exhibit][q116]
  
A.VRF-aware IS-IS  
B.Multi-process IS-IS  
C.IS-IS version 2  
D.Single-topology IS-IS

Answer:  D 

---

## Q117
What mechanism should you choose to prevent unicast flooding?
  
A.Make sure that all end systems are connected to the network with a single physical connection.   
B.Use control plane policing (CPP) to limit unicast flooding.   
C.Configure the ARP cache timers to be longer than the switch forwarding cache (CAM) timers.   
D.Configure the switch forwarding cache (CAM) timers to be longer than the ARP cache timers.

Answer:  D

---

## Q118
How is a targeted LDP session different from a standard LDP session? 
  
A.Targeted LDP requires SDP to be enabled   
B.Targeted LDP requires RSVP to be enabled   
C.Targeted LDP uses unicast hello messages to peer with other devices   
D.Targeted LDP is used only for neighbors on different segments

Answer:  C

---

## Q119
Which two application protocols require application layer gateway support when using NAT on a Cisco router? (Choose two.)
  
A.SIP   
B.HTTP   
C.FTP   
D.SMTP   
E.POP3 

Answer:  A, C 

---

## Q120
What command can you configure on a router so that traffic generated from the router is policy-router?
  
A.Ip route-map   
B.Ip policy   
C.Ip local policy   
D.Ip route-cache policy

Answer:  C

---

## Q121
In which order of magnitude (time) is delay/latency measured when you use wide metrics in EIGRP? 
  
A.tens of microseconds  
B.picoseconds  
C.nanoseconds  
D.microseconds 

Answer:  B

---

## Q122
In RSTP, which event would cause a topology change?
  
A.Edge ports transitioning to the forwarding state   
B.Non-edge ports transitioning to the forwarding state   
C.Non-edge ports transitioning to the discarding state   
D.Edge ports transitioning to the discarding state

Answer:  B

---

## Q123 
Refer to the Exhibit. Which two statements about the given MPLS VPN ate true? (Choose two.) 
![exhibit][q123]  

A.It includes four CE routers.   
B.Router A and router 1 must be BGP neighbors.   
C.It includes four P routers.   
D.It includes two CEs and two Pes.   
E.Only one connection is outside the ISP network. 

Answer:  C D 

---

## Q124
Which three actions are required when configuring NAT-PT? (Choose Three)\
  
A.Specify an IPv4-to-IPv6 translation   
B.Specify an IPv6-to-IPv4 translation   
C.Specify a ::/32 prefix that will map to an IPv6 address   
D.Specify a ::/96 prefix that will map to an IPV4 address   
E.Specify a ::/48 prefix that will map to a MAC address   
F.Enable NAT-PT globally

Answer:  A, B, D 

---

## Q125
Which two statements about PPP CHAP authentication are true? (Choose two) 
  
A.It is a one-way authentication method  
B.It uses a secret password, which is sent across the link for authentication  
C.It supports clear-text passwords  
D.It is configurable only on PPP callout links  
E.It uses a configured username and password to authenticate a host 

Answer:  A, E 

---

## Q126
Which escape sequence must you use to enter special characters as part of a key string? 
  
A.CTRL+S   
B.CTRL+P   
C.CTRL+K   
D.CTRL+V

Answer:  D

---

## Q127
Drag and drop each IS-IS PDU type from the left onto its purpose on the right  
![exhibit][q127]

Answer: 1, 2, 4, 3
URL: https://sites.google.com/site/amitsciscozone/home/is-is/is-is-packets

---

## Q128
Which two statements about route summarization are true? (Choose two.) 
  
A.RIP, IGRP, and EIGRP can automatically summarize routing information at network address boundaries.   
B.EIGRP can automatically summarize external routes.   
C.The area range command can aggregate addresses on the ASBR.   
D.The summary-address command under the router process configures manual summarization on RIPv2 devices.   
E.The ip classless command enables classful protocols to select a default route to an unknown subnet on a network with other known subnets.

Answer:  A, E 

---

## Q129
In which two modes do IPv6-in-IPv4 tunnels operate? (Choose two.) 
  
A.tunnel mode  
B.transport mode  
C.6to4 mode  
D.4to6 mode  
E.ISATAP mode 

Answer:  C, E

---

## Q130
Which PIM multicast type is designed to be used for many-to-many applications within individual PIM domains? 
  
A.PIM-DM  
B.Bidir-PIM  
C.PIM-SM  
D.SSM 

Answer:  B

---

## Q131
Drag and drop EIGRP query condition on the left to the corresponding action taken by the router on the right  
![exhibit][q131]

Answer: 1:3, 2:1, 3:4, 4:2

---

## Q132 
Refer to the exhibit. Which two configurations must you apply to R2 so that it correctly translates the Internal to a public IP address? (Choose two.)  
![exhibit][q132]
  
A.![exhibit][q132a]  
B.![exhibit][q132b]  
C.![exhibit][q132c]  
D.![exhibit][q132d]  
E.![exhibit][q132e]

Answer:  B E

---

## Q133
Which interface configuration task enables MLD on the interface?
  
A.Setting an IPv6 address   
B.Enabling IGMPv3   
C.Configuring SSM   
D.Configuring PIM6

Answer:  D
URL: http://dtdccie.blogspot.com/2015/03/mld-multicast-listener-discovery.html

---

## Q134 
Which three configuration settings must match for switches to be in the same MST region? (Choose three) 
  
A.Region name  
B.Password  
C.VLAN-to-instance assignment  
D.Domain name  
E.Revision number  
F.VLAN names 

Answer:  A C E 

---

## Q135
Refer to the exhibit. If router R1 is configured to run IS-IS with given configuration and all interfaces are up/up, what action must you take so that the Ethernet 0/0 netwrok can be advertised to potential IS-IS neighbors on the E0/1 interface ? 
![exhibit][q135]
  
A.Configure the ip router isis command on R1's interface E0/1.   
B.Configure an NSAP address on R1.   
C.Add the network 10.10.30.1 0.0.0.0 command to the R1 IS-IS process.   
D.Add the network 10.10.20.1 0.0.0.0 command to the R1 IS-IS process.

Answer:  A

---

## Q136
Drag and drop each step in the uRPF packet-forwarding from the left into the correct order of operations on the right  
![exhibit][q136]

Answer:  
![exhibit][q136a]

---

## Q137
Drag and drop each Cisco Performance Monitor component from the left onto the matching statement on the right  
![exhibit][q137]

Answer:  
![exhibit][q137a]

---

## Q138
Drag and drop the OSPFv3 LSA type on the left to the functionality it provides on the right  
![exhibit][q138]

Answer:
![exhibit][q138a]

---

## Q139
Which two statements about root guard are true? (Choose two) 
  
A.It allows unknown devices to participate in STP   
B.It automatically re-enables blocked ports   
C.It requires the administrator to manually re-enable ports that have been blocked   
D.It supports the errdisable-timeout command   
E.It automatically error-disables a port when PortFast is enabled   
F.It blocks BPDUs from unknown devices 

Answer:  A, B  
URL: https://www.cisco.com/c/en/us/support/docs/lan-switching/spanning-tree-protocol/10588-74.html

---

## Q140
Drag and drop the EIGRP query condition on the left to the corresponding action taken by the router on the right  
![exhibit][q140]

Answer: 2:1, 4:2, 1:3, 2:4  

---

## Q141
How should voice traffic be marked for DSCP in a standard QoS policy? 
  
A.AF21   
B.EF   
C.CS3   
D.AF41

Answer:  B  

---

## Q142
Which two statements about BGP best-path selection are true? (Choose two) 
  
A.The weight attribute is advertised to peers   
B.A route that originates from iBGP peers is preferred   
C.The route with the highest local preference is preferred   
D.A route that originates from a router with a higher BGP router ID is preferred   
E.The route with the lowest MED is preferred   
F.The lowest weight advertised is preferred

Answer:  C, E  

---

## Q143
Which statement about BGP synchronization rule is true?
  
A.A BGP router with synchronization enabled does not advertise its eBGP learned routes to its iBGP peers unless it has learned or verified this route on its routing table through a IGP   
B.A BGP router with synchronization enabled does not advertise its eBGP learned routes to its eBGP peers unless it has learned or verified this route on its routing table through an IGP   
C.A BGP router with synchronization enabled does not advertise its BGP learned routes to its iBGP peers unless it has learned or verified this route on its routing table through an iGP   
D.A BGP router with synchronization enabled does not advertise its iBGP learned routes to its eBGP peers unless it has learned or verified this route on its routing table an IGP

Answer:  D

---

## Q144
Drag and drop each description from the left onto the corresponding IP multicast protocol on the right  
![exhibit][q144]

Answer:  
![exhibit][q144a]

---

## Q145
Drag and drop the BGP attribute on the left to the correct category on the right. Not all options will be used.  
![exhibit][q145]

Answer: BGP Well-known Mandatory Attribute AS_Path BGP Optional Nontransitive Attributes Cluster List Originator ID BGP Optional Transitive Attributes Community 

---

## Q146
Which two statements about Management Plane protection are true? (Choose two.) 
  
A.It can handle management traffic when IP Cisco Express Forwarding is disabled.   
B.It supports in-band and out-of-band management interfaces.   
C.It is enabled by default, but it allows all management protocols to pass freely through all interfaces until it is configured.   
D.It supports the SNMP, SSH, TFTO, and HTTP management protocols.   
E.It provides granular control over the management protocols that are allowed on an interface.   
F.It works only on out-of-band management interfaces.

Answer:  B, D  

---

## Q147
Drag and drop the implementation steps on the left to the corresponding order on the right when configuring a L3 VxLAN gateway.  
![exhibit][q147]
Answer:  
![exhibit][q147a]

---

## Q148
Drag and drop statement about QoS features on the left to the matching QoS feature on the right  
![exhibit][q148]

Answer:  
![exhibit][q148a]

---

## Q149
Drag and drop the PPPoE packet type on the left to the corresponding description on the right.  
![exhibit][q149]

Answer:
![exhibit][q149a]

---

## Q150
Drag and Drop the NAT operations on the left to the correct sequential order on the right.  
![exhibit][q150]

Answer: Step 1 ----- Check the inbound Access list Step 2 ---- Check the policy routing Step 3 ---- Check the IP routing table Step 4 ---- translate the inside local to the outside global Step 5 ---- Check the outbound Access list Step 6 ---- inspect CBAC 

---

## Q151
Which two statements about MLD snooping are true? (Choose two)
  
A.MLD protocol messages can be sent in both IGMPv4 and ICMPv4 formats.   
B.It supports private VLANs.   
C.It limits the Layer 2 multicast traffic that is generated by routing protocols.   
D.PFC modes support MLD version 2 only.   
E.The MLD snooping querier requires the VLAN interface to be configured with an IPv6 address.

Answer:  B, E  

---

## Q152
Which metric vectors are stored but are not used by default in EIGRP?
  
A.Bandwidth and delay   
B.Load and reliability   
C.Load and bandwidth   
D.Reliability and delay

Answer:  B 

---

## Q153
Drag and drop each BGP attribute on the left into the correct priority order in which the attributes are preferred when determining the best path on the right. 
![exhibit][q153]

Answer:  
![exhibit][q153a]

---

## Q154
How can you prevent routing loops when performing mutual redistribution between two OSPF domains on multiple routes? 
  
A.No action is required, OSPF prevents routing loops by design   
B.Prevent routes from being redistributed into their original OSPF domain   
C.Redistribute only external routes between OSPF domains   
D.Make sure that the redistributing routes are members of Area 0 in both OSPF domains

Answer:  B 

---

## Q155
What are two effects of migration a network from PVST+ to MST? (Choose two) 
  
A.BPDU filter is automatically enabled   
B.BPDU guard is automatically disabled   
C.PortFast is automatically disabled   
D.UplinkFast is automatically disabled   
E.Root guard is automatically enabled   
F.BackboneFast is automatically disabled

Answer:  D, F 

---

## Q156
Drag and drop the IPv6 discovery message on the left to the corresponding description on the right. 
![exhibit][q156]

Answer:  
![exhibit][q156a]

---

## Q157
Drag and drop each EIGRP packet type from the left onto the matching description on the right. 
![exhibit][q157]

Answer:  
![exhibit][q157a]

---

## Q158
Which two options are two problems that Bridge Assurance can protect against? (Choose two) 
  
A.Ports being put into a root-inconsistent state.   
B.The forwarding of data traffic after the spanning tree algorithm is stopped.   
C.Slow convergence time after a topology change.   
D.Unidirectional link failures.   
E.BPDU flooding.

Answer:  B D 

---


## Q159
Which command can you enter to disable logging for VTY lines? 
  
A.no logging console   
B.no logging trap   
C.no logging buffer   
D.no logging count   
E.no logging monitor

Answer:  E 

---

## Q160
Drag and Drop the OpenStack projects from the left onto their function on the right
![exhibit][q160]

Answer:
![exhibit][q160a]

---

## Q161
Which statement best describes IPv6 RA Guard?
  
A.It blocks unexpected IPv6 router announcements on a link   
B.It filters authorized IPv6 device advertisements on a link   
C.It redirects authorized device hello messages   
D.It validates ingress hello messages on a port

Answer:  A 

---

## Q162
Which statements about IGMP filtering are true?
  
A.It allows Anycast RP to operate within a single AS   
B.It can be implemented on Layer-3 routed ports using the ip igmp access-list command   
C.It eliminates the need for a multicast RP   
D.It can be implemented on Layer-2 switching using IGMP profiles   
E.It supports IGMPv3 traffic only

Answer:  A, B  

---

## Q163
Which two statements about MSDP are true? (Choose two)
  
A.It interconnects PIM-SM domains   
B.It is supported both for IPv4 and IPv6 multicast deployments   
C.It is encapsulated into PIM packets   
D.MPLS is required to establish MSDP peering   
E.MSDP peers are established using multiprotocol BGP   
F.It is encapsulated into UDP segments

Answer:  A, E  

---

## Q164
Which statement about shaped round robin queuing is true? 
  
A.Queues with higher configured weights are serviced first.  
B.The device waits a period of time, set by the configured weight, before servicing the next queue.  
C.The device services a single queue completely before moving on to the next queue.  
D.Shaped mode is available on both the ingress and egress queues. 

Answer:  A  

---

## Q165
Which statement about BGP synchronization rule is true? 
  
A.A BGP router with synchronization enabled does not advertise its eBGP learned routes to its iBGP peers unless it has learned or verified this route on its routing table through a IGP   
B.A BGP router with synchronization enabled does not advertise its eBGP learned routes to its eBGP peers unless it has learned or verified this route on its routing table through an IGP   
C.A BGP router with synchronization enabled does not advertise its BGP learned routes to its iBGP peers unless it has learned or verified this route on its routing table through an iGP   
D.A BGP router with synchronization enabled does not advertise its iBGP learned routes to its eBGP peers unless it has learned or verified this route on its routing table an IGP

Answer:  D

---

## Q165
Which two statements about HDLC operations in asynchronous balanced mode are true? (Choose two)
  
A.Each device must negotiate with its neighbors before sending frames   
B.Each device must negotiate with its neighbors to recover framing errors   
C.The initiating device sends a DTE frame   
D.Either device can initiate transmission of frames   
E.Either device can send frames at any time

Answer:  D, E  

---

## Q166 
![exhibit][q166]  
Which two statements about the VPN solution are true? (Choose two.)
  
A.Customer A and customer B will exchange routes with each other.   
B.R3 will advertise routes received from R1 to R2.   
C.Customer C will communicate with customer A and B   
D.Communication between sites in VPN1 and VPN2 will be blocked.   
E.R1 and R2 will receive VPN routes advertised by R3.

Answer:  C, E

---

## Q167
Which GET VPN component maintains security policies?
  
A.P   
B.PE   
C.GDOI   
D.group member   
E.key server   
F.CE 

Answer:  E  

---

## Q168
How can you prevent routing loops when performing mutual redistribution between two OSPF domains on multiple routers?
  
A.No action is required, OSPF prevents routing loops by design   
B.Make sure that the redistributing routers are members of Area 0 in both OSPF domains   
C.Redistribute only external routers between the OSPF domains   
D.Prevent routes from being redistributed into their original OSPF domain

Answer:  D  

---

## Q169
Which two statements about IPv6 PACLs are true? (Choose two)
  
A.They are supported only on ingress   
B.They are supported only for L2   
C.They are supported only for L3   
D.They require an IPv6 access list to be configured first   
E.They are supported only on egress

Answer:  A, D  

---

## Q170
Drag and drop each SNMP feature from the left onto the correct SNMP version on the right 
![exhibit][q170]

Answer:  
![exhibit][q170a]

---

## Q171
Which two conditions can cause unicast flooding? (Choose two)
  
A.multiple MAC addresses in the Layer 2 forwarding table   
B.recurring TCNs   
C.RIB table overflow   
D.symmetric routing   
E.forwarding table overflow

Answer:  B, E  

---

## Q172
Which protocol is the encapsulating protocol for mtrace packets? 
  
A.ICMP  
B.IGMP  
C.PIM  
D.GRE 

Answer:  B 

---

## Q173
When you deploy DMVPN, what is the purpose of the command crypto isakmp key ciscotest address 0.0.0.0 0.0.0.0? 
  
A.It is configured on hub and spoke router to establish peering   
B.It is configured on hub to set the pre-shared key for the spoke routers   
C.It is configured on the spokes to indicate the hub router   
D.It is configured on the Internet PE routers to allow traffic to traverse the ISP core

Answer:  B 

---

## Q174
What two values are required to implement an EIGRP named configuration? (Choose two.) 
  
A.virtual-instance-name  
B.address-family  
C.router-id  
D.subnet-mask  
E.process-id 

Answer:  A, B 

---

## Q175
Which two statements about CEF polarization are true? (Choose two)
  
A.The AND operation is performed on the higher-order bits of the source and destination IP address   
B.A single link is chosen for all flows   
C.The AND operation is performed on the lower-order bits of the source and destination IP address   
D.After the XOR process, the flow is processed in the distribution Layer with a different hashing algorithm   
E.It can be prevented by alternating the hashing inputs   
F.When enabled, it allows all links to be used efficiently for different traffic flows

Answer:  B, E  
URL: https://networklessons.com/cisco/ccie-routing-switching-written/cef-polarization/

---

## Q176
Which three device roles does 802.1x require? (Choose three)
  
A.An endpoint device that verifies network credentials   
B.A server that facilitates authentication   
C.A network device that grants client authentication   
D.A server that assigns network-level access   
E.An endpoint device that sends authentication credentials   
F.A network device that relays authentication credentials

Answer:  D, E, F  

---

## Q177
What is the current order of the VSS initialization process? Drag and drop the actions on the left to the correct initialization step on the right 
![exhibit][q177]

Answer:  
![exhibit][q177a]

---

## Q178
Drag each statement about Cisco EEM policies on the left to the matching type of EEM policy on the right
![exhibit][q178]

Answer:  
![exhibit][q178a]

---

## Q180
Drag and drop the description on the correct EIGRP term in the right 
![exhibit][q180]

Answer: E-1, B-2, D-3 

---

## Q181
How does Control Plane Policing protect the route processor? 
  
A.It disables access to the control plane during an attack.   
B.It treats the route processor as a separate entity within MQC  
C.It dynamically enables ingress ACLs on selected interfaces.   
D.It marks non-essential traffic and moves it to the Scavenger class.

Answer:  B 

---

## Q182
Which two options describe the effect of configuring an interface as passive under OSPF? (Choose two)
  
A.The interface process OSPF hello packets and also sends hello packets   
B.An adjacency cannot be established, and the interface is included in the routing protocol update   
C.An adjacency cannot be established, and the interfaces is not included in the routing protocol update   
D.An adjacency can be established, and the interface is not included in the routing protocol update   
E.The interface processes OSPF hello packets but does not send hello packets

Answer:  B, E  

---

## Q183
Which feature can you implement to most effectively protect customer traffic in a rate-limited WAN Ethernet service?
  
A.Q-in-0   
B.OiffServ   
C.HCBWFQ   
D.lntServ with RSVP   
E.The IPsec VTI qos pre-classify command

Answer:  C  

---

## Q184
Which queuing strategy ignores packet markings?
  
A.CQ   
B.FIFO   
C.LLQ   
D.WFQ   
E.WRED   
F.CBWFQ 

Answer:  B  

---

## Q185
Which two statements are true about VPLS? (Choose two.)
  
A.It can work over any transport that can forward IP packets.   
B.It can carry a single VLAN per VPLS instance.   
C.It includes automatic detection of multihoming.   
D.It provides integrated mechanisms to maintain First Hop Resiliency Protocols such as HSRP, VRRP, or GLBP.   
E.It relies on flooding to propagate MAC address reachability information.

Answer:  B E  

---

## Q186
Which command can you enter to configure a Cisco router running OSPF to propagate the static default route 0.0.0.0 0.0.0.0 172.31.15.1 within the OSPF process?
  
A.Default-information originate   
B.Redistribute static   
C.Redistribute static subnets   
D.Redistribute static metric 1 subnets

Answer:  A  

---

## Q187
Which two conditions must be met by default to implement the BGP multipath feature? (Choose two)
  
A.MPLS must be enabled.   
B.The next-hop routers must be the same.   
C.The next-hop routers must be different.   
D.Route reflectors must be enabled.   
E.All attributes must have the same values.

Answer:  C, E  

---

## Q188
How does an IPv6 host automatically generate a global address?
  
A.It prepends its interface identifier to the network prefixes contained in Router Solicitation messages.   
B.It appends its interface identifier to the network prefixes contained in Router Advertisement messages.   
C.It appends its interface identifier to the network prefixes contained in Router Solicitation messages.   
D.It prepends its interface identifier to the network prefixes contained in Router Advertisement messages

Answer:  B  

---

## Q190
Drag and drop the multiprotocol BGP feature on the left to the corresponding description on the right. 
![exhibit][q190]

Answer:  
![exhibit][q190a]

---

## Q191 
Refer to the exhibit. What happens to a TCP packet that is received on interface GigabitEthernet0/0/0.100, which has DF bit set to 1, and packet has a valid destination?  
![exhibit][q191]
  
A.The packet is matched by route-map loo and the DF bit is set to 0   
B.The packet is not matched by route-map loo and the DF bit is left as it was   
C.The packet is matched by route-map loo and the DF bit is left as it was   
D.The packet is not matched by route-map loo and the DF bit is set to 0

Answer:  B 

---

## Q192
Which two statements about MLD are true? (Choose two.)
  
A.There are three subtypes of MLD query messages.   
B.When a single link supports multiple interfaces, only one interface is required to send MLD messages.   
C.MLD is a subprotocol of PIMv6.   
D.When a single link supports multiple interfaces, all supported interfaces are required to send MLD messages.   
E.The code section in the MLD message is set to 1 by the sender and ignored by receivers   
F.MLD is a subprotocol of ICMPv6.

Answer:  B, F  

---

## Q193
Which two statements about the host address 10.88.100.10/13 are true (choose two)
  
A.The network address is 10.64.0.0   
B.The network address is 10.88.100.0   
C.The broadcast address is 10.64.255.255   
D.The broadcast address is 10.88.255.255   
E.The network address is 10.88.0.0   
F.The broadcast address is 10.95.255.255

Answer:  E, F  

---

## Q194
Which statement about OSPF multiaccess segments is true?
  
A.The designated router is elected first.   
B.The designated and backup designated routers are elected at the same time.   
C.The router that sent the first hello message is elected first.   
D.The backup designated router is elected first.

Answer:  D 

---

## Q195
What terminal line command can you enter to prevent a router from attempting a Telnet connection in response to an incorrect host name entry at the EXEC prompt?
  
A.Transport preferred none   
B.Transport output none   
C.No ip domain-lookup   
D.Transport input none   
E.Logging synchronous

Answer:  A  
URL: http://lostintransit.se/2011/05/18/transport-preferred-none/

---

## Q196
When you implement CoPP on your network, what is its default action?
  
A.Rate-limit bidirectional traffic to the control plane.   
B.Permit all traffic   
C.Block all traffic   
D.Drop management ingress traffic to the control plane.   
E.Monitor ingress and egress traffic to the control plane by using access groups that are applied to the interface

Answer:  B  

---

## Q197
Which three criteria are used for stackwise election of a master switch?
  
A.lowest MAC address   
B.Vl.AN revision number   
C.longest uptime   
D.user-selected priority   
E.highest MAC address   
F.I0S version number 

Answer:  A, C, D  

---

## Q198
Which two statements about marking fields are true? (Choose two)
  
A.The 3 priority bits are in 802.10/P.   
B.The Frame Relay OE field is in the IP header and is 1 bit long.   
C.The IP DSCP field is in the IP header and is 6 bits long.   
D.The ToS 6 bits are in the IP header   
E.The IP Precedence field is in the IP header and is 4 bits long.

Answer:  C, D

---

## Q199
Which two statements about 6to4 tunnels are true? (Choose two.)
  
A.They support point-to-multipoint traffic   
B.They support point-to-point traffic   
C.They generate an Pv6 prefix using a common IPv4 address.   
D.They allow IPv4 packets to travel over IPv6 infrastructure without modification   
E.They encapsulate IPv6 packets, which allows the packets to travel over IPv4 infrastructure.   
F.They support OSPF and EIGRP traffic

Answer:  A, E  

---

## Q200
Which two statements about the client-identifier in a DHCP pool are true? (Choose two.)
  
A.It specifies a unique identifier that is used only for BOOTP requests.   
B.It specifies a hardware address for the client   
C.It is specified by appending 01 to the MAC address of a DHCP client   
D.It requires that you specify the hardware protocol.   
E.It specifies a unique identifier that is used only for DHCP requests.

Answer:  C, E  

---

## Q201
Which three options describe characteristics of a link state routing protocol? (Choose three)
  
A.It provodes faster convergence as opposed to distance vector routing protocols   
B.It uses hop count in the metric calculation to detrmine the best path   
C.It uses cost in the metric alculation to determine the best path   
D.It only has a neighbor routing table   
E.It is topology driven and has an overall overview of the network   
F.It is better in detecting suboptimal routing

Answer:  A, C, E  

---

## Q202
In which 802.1D port state are the root bridge, the root port, and the designated port(s) elected?
  
A.Forwarding   
B.Learning   
C.Listening   
D.Blocking   
E.Disabled

Answer:  C 

---

## Q203
What characteristic of OSPFv3 LSAs enables support for prefix suppression?
  
A.Router-LSAs and Network-LSAs are flooded into the entire OSPF domain.   
B.Router-LSAs and Network-LSAs do not contain prefix information.   
C.Router-LSAs and Network-LSAs do not contain topology information.   
D.Router-LSAs and Network-LSAs are flooded only on the local link.

Answer:  B 

---

## Q204 
Refer to the exhibit. Which two actions can you take to allow the network 1 72.29.224.0/24 to be reachable from peer 192.168.250.53? (Choose two)  
![exhibit][q204]
  
A.Modify the outbound route map to permit all additional traffic.   
B.Configure soft reconfiguration to peering 192.168.250.53   
C.Modify the community list to match community 64513:64090 attached to 172.29.224.0/24.   
D.Configure additional address families to peering 192.168.250.53   
E.Modify the inbound route map to permit all additional traffic

Answer:  A, C 

---

## Q205
Which two statements about OSPFv3 are true? (Choose two.)
  
A.It supports unicast address families for IPv4 and IPv6.   
B.It supports unicast address families for IPv6 only.   
C.It supports only one address family per instance.   
D.It supports the use of a cluster ID for loop prevention.   
E.It supports multicast address families for IPv4 and IPv6.   
F.It supports multicast address families for IPv6 only.

Answer:  A, C  

---

## Q206
Which three configuration settings must match for switches to be in the same MST region? (Choose three)
  
A.Region name   
B.Password   
C.VLSN-to-instance assignment   
D.Domain name   
E.Revision number   
F.VLAN names 

Answer:  A, C, E  

---

## Q207
Which two options are restrictions of BGP Outbound Route Filtering? (Choose two.)
  
A.It requires access lists to match routes.   
B.It can be used only with eBGP.   
C.It can be used only with iBGP.   
D.It can be used only with IPv4 multicast.   
E.Multicast is not supported.

Answer : B, E  

---

## Q208
Which attribute is not part of the BGP extended community when a PE creates a VPN-IPv4 route while running OSPF between PE-CE? 
  
A.OSPF domain identifier  
B.OSPF route type  
C.OSPF router ID  
D.MED  
E.OSPF network type 

Answer:  E  

---

## Q209
If OSPF fast hellos are configured on an interface and the hello-multiplier is set to 10, how frequently are hello packets are sent?
  
A.every 200 milliseconds   
B.every 50 milliseconds   
C.every 100 milliseconds   
D.every 500 milliseconds

Answer:  C  

---

## Q210
Which function does PHP perform?
  
A.popping the bottom label one hop before the egress LSR   
B.popping the two bottommost labels one hop before the egress LSR   
C.popping the bottom label at the egress LSR   
D.popping the top label at the egress LSR   
E.popping the two topmost labels one hop before the egress LSR   
F.popping the two label one hop before the egress LSR

Answer:  D  

---

## Q211
Which option is the result if two adjacent routers are configured for OSPF with different process IDs?
  
A.The router establishes an adjacency and exchange routes are unreachable   
B.The routers establish an adjacency, but route exchange fails   
C.The routers are unable to establish an adjacency   
D.The routers establish an adjacency and exchange routers, and the routers are reachable

Answer:  D 

---

## Q212
Which problem can result when private AS numbers are included in advertisements that are sent to the global Internet BGP table?
  
A.The prefixes sent with private AS numbers are always discarded on the Internet.   
B.The prefixes sent with private AS numbers are always tagged as invalid on the Internet.   
C.The prefixes sent with private AS numbers lack uniqueness, which can lead to a loss of connectivity.   
D.The prefixes sent with private AS numbers are sometimes tagged as invalid on the Internet.

Answer:  C  

---

## Q213
How is traffic directed to a 6RD tunnel interface from the native IPv6 Internet?
  
A.Traffic is sent encapsulated in IPv4 from the native IPv6 host directly to the tunnel interface   
B.Traffic is routed to the 6RD gateway of the ISP and encapsulated over IPv4 to the tunnel interface   
C.Traffic is routed to the nearest public gateway and encapsulated over IPv4 to the tunnel interface   
D.Traffic is routed to the nearest public relay and encapsulated over IPv4 to the tunnel interface

Answer:  A 

---

## Q215
Which MLD message type does a host send to join multicast groups?
  
A.Join/Prune   
B.Done   
C.Hello   
D.Query   
E.Assert   
F.Report

Answer:  F  

---

## Q216 
Refer to the exhibit. Based on the output shown, how are the OSPFv3 address-families configured for this router?
![exhibit][q216]
  
A.The IPv6 address family is configured for both area 0 and area 1   
B.The IPv4 address family is configured for area 1, IPv6 for area 0   
C.The IPv4 address family is configured for area 0, IPv6 for area 1   
D.The IPv4 address family is configured for both area 0 and area 1

Answer:  B

---

## Q217
Which command must you configure on a device so it can establish an IPv6-in-IPv4 IPsec tunnel? 

A.ip cef  
B.vrf context vrf-name  
C.mpls ip  
D.ipv6 unicast-routing  

Answer:  D  

---

## Q218
Which two statements about PIM snooping are true? (Choose two) 

A.Auto-RP traffic is not affected by PIM Snooping and is always flooded  
B.Prune messages are forwarded to the router listed in the message payload  
C.Join messages are flooded on all switch ports  
D.Prune messages are flooded on all switch ports
E.Traffic for groups operating in dense mode is forwarded to the downstream routers

Answer:  A, B  

---

## Q220
In which scenario can you host the most instances on a server? 

A.Using microservices application  
B.Using virtual machines in containers  
C.Using only containers  
D.Using only virtual machines  
E.Using containers in virtual machines  

Answer:  C  

---

## Q221
Which two options are requirements to implement 6VPE? (Choose two) 

A.MP-BGP IPv6+label exchange  
B.Any transport over MPLS  
C.6-in-4 tunnels between PEs  
D.IPv4/IPv6 dual-stack in core  
E.MP-BGP VPNv6 exchange  
F.MPLS between PEs  

Answer:  E, F 

---

## Q222
Which are three basic elements of Cisco Performance Monitor? (Choose three) 

A.master controller  
B.class  
C.SLA  
D.policy  
E.border router  
F.flow record

Answer:  B, D, F  

---

## Q223
Which two statements about PPP CHAP authentication are true? (Choose two) 

A.It supports clear-text passwords  
B.It uses a configured username and password to authenticate to a host  
C.It uses a secret password, which is sent acress the link for authentication  
D.It is a one-way authentication method  
E.It is configurable only on PPP callout links

Answer:  B, D  

---

## Q224
Drag and drop the EIGRP query condition on the left to the corresponding action taken by the router on the right. 
![exhibit][q224]

Answer: 2:1, 4:2, 1:3, 2:4 

---

## Q225
Which packet is sent out by the DIS in IS-IS? 

A.LSP  
B.CSNP  
C.LSDB  
D.PSNP

Answer:  B 

---

## Q226
What mechanism should you choose to prevent unicast flooding? 

A.Configure the ARP cache timers to be longer than the switch forwarding cache (CAM) timers  
B.Use control plane policing (CPP) to limit unicast flooding  
C.Make sure that all end systems are connected to the network with a single physical connection  
D.Configure the switch forwarding cache (CAM) timers to be longer that the ARP cache timers  

Answer:  D  

---

## Q227
Which three terms are used to describe an OS-level virtualization method for deploying and running distributed applications? (Choose three) 
  
A.Containerization  
B.Container networking  
C.Container-based virtualization  
D.Virtualized networking  
E.Application containerization  
F.Container Stack G. Shared Kernel 

Answer:  A, C, E  

---

## Q229
Which feature monitors and reports events and can take corrective action in response to events it observes? 

A.EEM  
B.Syslog  
C.IP Accounting  
D.Netflow  

Answer:  A 

---

## Q230
Refer to the exhibit. You are configuring Router 1 and Router 2 for L2TPv3 tunneling. Which two additional configurations are required to enable Router1 and Router 2 to establish the tunnel? (Choose two)  
![exhibit][q230]
  
A.Router1 must be configured to encapsulate traffic by using L2TPv3 under the pseudowire-class R1 to R2  
B.Cisco Discovery Protocol must be configured on interface FastEthernet 1/0 on router1  
C.An IP address must be configured on interface FastEthernet 1/0 on router1  
D.Loopback 0 on Router1 must be advertised to Router2  
E.Cisco Express Forwarding must be disabled on Router1 

Answer:  A, D 

---

## Q231
What value is used to determine the multicast designated forwarder on a segment

A.he device with the lowest multicast routing distance to the sender  
B.The unicast routing metric to the RP  
C.The device with the highest loopback address  
D.The PIM priority setting on the interface  
E.The device with the highest multicast routing distance to the sender  
F.The device with the lowest loopback  

Answer:  A 

---

## Q232 
Which two statements about MLPPP are true? (Choose two) 
  
A.It can bundle up to six T-1 interfaces  
B.It supports fragmentation over multiple point-to-point links  
C.It requires a group number to bundle the interfaces  
D.The multilink interface number must match the group number  
E.The MLPPP encapsulation process adds 8 extra bytes to each packet 

Answer:  B, C 

---

## Q232 
What does a nonzero forwarding address indicate in a type-5 LSA? 
  
A.It indicates that this link-state ID is eligible for ECMP.  
B.It indicates that this router should have an OSPF neighbor relationship with the forwarding address before using this link-state ID  
C.It indicates that the receiving router must check that the next hop is reachable in its routing table before using this link-state ID  
D.It indicates that traffic can be directly routed to this next hop in shared segment scenarios where the external route source is directly connected. 

Answer:  D  

---

## Q233 
Which two of the following are Cisco UCS default user roles? (Choose two)
  
A.Administrator   
B.LAN Administrator   
C.Server Equipment Administrator   
D.Server Resource Administrator   
E.FCoE Administrator

Answer:  A, C

---

## Q234 
With which ISs will an IS-IS Level 1 IS exchange routing information? 
  
A.Level 1 ISs  
B.Level 1 ISs in the same area  
C.Level 1 and Level 2 ISs  
D.Level 2 ISs 

Answer:  B  

---

## Q235
Refer to the exhibit. Which two statements correctly, describe the final state of the routing table if the R1 IS-type is changed to Level 1 only? (Choose two)  
![exhibit][q235]
  
A.The 10.10.10.10/32 route will be in the routing table   
B.The 192.168.2.0/30 route will not be in the routing table   
C.The 10.10.10.10/32 route will not be in the routing table   
D.The 192.168.2.0/30 route will be in the routing table

Answer:  C, D

---

## Q236 
Which two options are mandatory components of a multiprotocol BGP VPN-IPv4 address? (Choose two)  
  
A.an area ID   
B.an IPv4 address   
C.a route distinguisher   
D.an MPLS label   
E.a system ID   
F.a route target.

Answer:  B, C  

---

## Q236
Refer the exhibit. Which option describes how a device with this configuration applies traffic matching? 
![exhibit][q236]
  
A.It matches all traffic in ACL 8  
B.It matches all traffic that has a DSCP marking of EF  
C.It matches all trafic in ACL 8 and all traffic that has a DSCP marking of EF  
D.It matches traffic in ACL 8 that has a DSCP marking EF  
E.It matches all traffic that has QoS markings 

Answer:  D 

---

## Q237 
Which feature disables MPLS PE checks on a router running OSPF?
  
A.A virtual-link   
B.The capability vrf-lite command   
C.An area filter   
D.A sham-link

Answer:  B  

---

## Q238 
Refer to the exhibit. Which two configurations must you apply to the master controller and the border router to provision them? (Choose two)  
![exhibit][q238]
  
A.![exhibit][q238a]  
B.![exhibit][q238b]  
C.![exhibit][q238c]  
D.![exhibit][q238d]

Answer:  B  

---

## Q239
What are two reasons for an OSPF neighbor relationship to be stuck in exstart/exchange state? (Choose two.)
  
A.Both routers have the same OSPF process   
B.Both routers have the same router   
C.There is an MTU mismatch.   
D.There is an area ID mismatch.   
E.There is an authentication mismatch.  

Answer:  B, C 

---

## Q240
Which are the three recommended steps to implement your Risk-based IoT Security Program? (Choose three)
  
A.Optimise   
B.Implement   
C.Assess   
D.Troubleshoot   
E.Analyze   
F.Formalize

Answer: C, B, F

---

## Q241
Which command can you enter to prevent IS-IS PDUs from using the full MTU size?
  
A.Metric-style wide   
B.Set-overloaded-bit on-startup wait-for-bgp suppress interievel   
C.Set-overload-bit on-startup 120   
D.No hello padding

Answer:  D

---

## Q242 
Refer to the exhibit. When a question mark is entered after bgp bestpath, only three options are visible. Which two BGP hidden options for the bgp bestpath command are valid? (Choose two)
![exhibit][q242]
  
A.bgp bestpath localpref ignore   
B.bgp bestpath as-path ignore   
C.bgp bestpath as-path multipath relax   
D.bgp bestpath compare-all  

Answer:  B, D

---

## Q243 
Which two statements about Metro Ethernet services are true? (Choose two)
  
A.EVP-Tree provides root-to-leaf and leaf-to-leaf connectivity, preventing root-to-root connectivity   
B.EVP-LAN provides point-to-point connectivity   
C.EVPL uses point-to-point EVCs between pairs of NNIs   
D.EPL provides a point-to-point multipoint service   
E.EP-LAN provides a single multipath LAN services to attached customers locations.   
F.EVPL uses 802.1Q tagging to differentiate between multiple private lines on an UNI

Answer:  B, E 

---

## Q244 
What are three valid HSRP states? (Choose two)
  
A.Full   
B.Learning   
C.INIT   
D.Established   
E.Speak   
F.Listen

Answer:  B, E, F 

---

## Q245
Refer to the exhibit. You are configuring the S1 switchport connecting to the client computer. What is the effect of the command mls qos map cos-dscp 0 8 16 24 32 40 46 56?  
![exhibit][q245]
  
A.Voice traffic is excluded from the default priority queue   
B.Voice packets are processed in the priority queue   
C.Voice packets are given a class selector of 5   
D.Video conferencing is marked CS3 

Answer:  A 

---

## Q246
Which three statements about AToM are true? (Choose three) 
  
A.It supports interworking for Frame Relay, PPP, and Ethernet, but not ATM   
B.IP CEF should be disabled on the PE routers   
C.The PE routers must share the same VC identifier   
D.It requires MPLS between the PE routers   
E.The attachment circuit is configured with the xconnect command   
F.It requires Layer 3 routing between the PE and CE router

Answer:  C, D, E 

---

## Q247
What are two effects of configuring the passive-interface command on a router running RIPv2? (Choose two) 
  
A.It enables the device to send broadcast updates   
B.It prevents the device from sending multicast updates   
C.It enables the device to accept multicast updates from other devices   
D.The device will ignore updates from other devices   
E.The device will not ignore updates from other devices

Answer:  B, E

---

## Q248
Refer to the exhibit. Which authentication method can the device use as an alternate to the pre-shared key?  
![exhibit][q248]
  
A.Clear-text   
B.Null   
C.Certificate   
D.802. 1x

Answer:  C 

---

## Q249
Which two statements about DTP are true? (Choose two) 
  
A.When two ports set to dynamic auto mode negotiates with one another, they agree to operate as trunk ports   
B.When a port set to dynamic auto mode negotiates with a port set to trunk mode, they agree to operate as trunk ports   
C.DTP must be unconditionally enabled on links between switches in order to deploy VTP   
D.DTP negotiates the trunk native VLAN along with the trunking mode   
E.Dynamic ports are vulnerable to attack from the rogue stations sending false DTP packets

Answer:  B, E

---

## Q250
Which two statements about TACACS+ are true? (Choose two)
  
A.It uses the UDP protocol to provide faster indication of a server failure  
B.It encrypts the TACACS+ header and the message body for enhanced security   
C.It combines authentication and authorization, which allows for faster communication between the IOS device and the TACACS server   
D.It supports multiple non-IP protocols, including AppleTalk Remote Access   
E.It allows privileges to be authorized on a per-user level

Answer:  B, E 

---

## Q251
Refer to the exhibit. Which two conclusions can you draw from this output? (Choose two)  
![exhibit][q251]
  
A.The packets was source-routed   
B.The device that produced the output uses the same interface to send and receive traffic to and from the device at 10.9.132.254   
C.The device at 192.168.5.119 is on the same subnet as the next hop for the device at 10.9.132.254   
D.The device at the 192.168.5.119 routing table has an ARP entry for the device at 1.9.132.254   
E.The device that produces the output uses different interfaces to send and receive traffic to and 
from the device at 10.9.132.254

Answer:  B, C 

---

## Q252
Which two statements about IPv6 RA guard are true? (Choose two)
  
A.It is supported in the ingress and egress directions   
B.It blocks unauthorized ICMPv6 Type 133 packets  
C.It blocks unauthorized ICMPv6 Type 134 packets   
D.It supports host mode and router mode   
E.It provides security for tunneled Ipv6 traffic

Answer:  C, D 

---

## Q253
Which are two functions of the master controller in PfR? (Choose two)
  
A.It learns the traffic path   
B.It perform traffic inspection  
C.It applies the policy   
D.It enforces the traffic path   
E.It provides network visibility

Answer:  C, ...

---

## Q254
Which two statements about the PIM Assert message are true? (Choose two)
  
A.It elects the device with the lowest IP address on the LAN segment as the PIM forwarder  
B.It elects the PIM router with the highest IP address on the LAN segment as the forwarder if remaining metrics are the same   
C.It determines which router connected to a common LAN segment becomes the PIM Designated Router   
D.It is triggered when multiple routers connected to a common LAN segment receive the same IGMP join request from a multicast receiver   
E.It elects the device with the lowest administrative distance to the multicast source as the PIM Designated Router   
F.It is triggered when multiple routers connected to a common LAN segment forward the same multicast packet

Answer:  D, F 

---

## Q255
Two routers are connected on a PPP link using CHAP authentication. By default, which value will routers use as their identification on the link? 
  
A.Their IP addresses on the connection link   
B.Their serial numbers   
C.Their interface numbers   
D.Their hostnames  

Answer:  D

---

## Q256
Which two roles are used by devices for building multicast trees using bidirectional PIM? (Choose two)
  
A.Candidate Rendezvous Point  
B.Bootstrap Router   
C.Rendezvous Point   
D.Designated Forwarder   
E.Mapping agent   
F.Pruning Router  

Answer:  C, D 

---

## Q257
With PBR and set ip next-hop configured on an incoming interface, how does the router forward the packet with the next-hop being unreachable? 
  
A.The next hop is added to the route table and the packet is policy routed   
B.The packet is policy routed   
C.The packet is dropped   
D.The packet is forwarded using the normal routing table

Answer:  D 

---

## Q258
Which two statements about IPv6 tunnels are true? (Choose two)
  
A.They are point-to-multipoint tunnels  
B.Sites use addresses from the 2002::/16 prefix   
C.They rely on GRE encapsulation   
D.They are point-to-point tunnels   
E.Sites use addresses from the link-local scope

Answer:  C, D 

---

## Q259
Which BGP command will prevent flapping routes from being injected into the routing table?
  
A.OSPF Loop Free Alternate  
B.IP Fast Reroute   
C.EIGRP DUAL   
D.bgp dampening

Answer:  D 

---

## Q260
Which protocol allows connections made by an NBMA network to dynamically learn connected addresses?
  
A.HDLC   
B.NHRP  
C.POP   
D.PPP  

Answer:  B

---

## Q261
Which description correctly describes Git?
  
A.Git is a version control system for tracking changes in files   
B.Git is a command-line utility for creating archives of files   
C.Git is a web-based repository for sharing files  
D.Git is a configuration management tool that automates provisioning

Answer:  A 

---

## Q262
One of your clients which is in the manufacture area, is after a solution in order to manage all his fog nodes. Which management tools best suits his needs?
  
A.Cisco Connected Grid Network Management System   
B.Cisco Prime Infrastructure   
C.Cisco Network Control System  
D.Cisco Fog Director

Answer:  B 

---

## Q263
Which statement correctly describes Ansible operations and playbooks?
  
A.Ansible is agent-based and uses playbooks formatted in YAML   
B.Ansible is agent-based and uses playbooks formatted in XML   
C.Ansible is agentless and uses playbooks formatted in XML   
D.Ansible is agentless and use playbooks formatted in YAML 

Answer:  D 

---

## Q264
Which three benefits of virtualizing the DMZ are true? (Choose three)
  
A.Orchestration   
B.Usage-based consumption model   
C.Service catalog   
D.Dynamic and automated service insertion with focus on security   
E.Analytics  
F.Per-app network functions and operation

Answer:  D, E, F 

---

## Q265
Which three campus fabric nodes is SD-Access architecture are true? (Choose three)
  
A.Fabric wireless access points   
B.Fabric border nodes   
C.Control plane nodes   
D.Virtual plane nodes   
E.Data plane nodes  
F.Fabric edge nodes

Answer:  B, C, F   

---

## Q269
Which three connectivity models for vEdge site architecture are true ?

A.Hybrid with fallback  
B.augmentation model  
C.secure tunnel  
D.secure virtual connectivity  
E.full SD-wan  
F.cloud provider  

Answer: A, C, E

---

## Q270
Which three statements correctly describe the encoding used NETCONF and RESTCONF ?

A.RESTCONF uses JSON-encoded data  
B.NETCONF used XML-encoded data  
C.NETCONF used YAML-encoded data  
D.RESTCONF uses XML-encoded data  
E.NETCONF used JSON-encoded data  
F.RESTCONF uses YAML-encoded data  

Answer: A, B, D

---

## Q266
Which two statements about MST are true? (Choose two.)   

A.Each MSTI sends its own independent BPDUs.  
B.An MSTI is a single PVST instance  
C.An MST region is defined by its name, configuration revision, and VLAN-to-instance mapping table  
D.IN an MST region, switches run a single IST and Zero or more additional MSTIs  
E.BPDUs carry VLAN-to-instance mapping information to switches in the same region                

Answer: B, C                                           

---

## Q267
Which two features are incompatible with Loop guard on a port? (Choose two)   

A.PortFast  
B.BPDU skew detection  
C.UplinkFast  
D.BackboneFast  
E.Root Guard       

Answer: A, E                                                    

---

## Q268
Which PHB type allows for the best interoperability with IP Precedence already used in the network?   

A. Assured Forwarding  
B. Class Selector  
C. Default  
D. Expedited Forwarding                

Answer: B                                           

---

## Q269
Drag each statement about VPN policies on the left into the matching VPN policy category on the right      
![exhibit][q269]

Answer:         
![exhibit][q269a]                

---

## Q270
Which two features of DMVPN are true? (Choose two)   

A. It offers configuration reduction  
B. It does not support spoke routers behind dynamic NAT  
C. It only supports remote peers with statically assigned addresses  
D. It requires IPsec encryption  
E. It supports multicast traffic             

Answer: A, E                                           

---

## Q271
![exhibit][q271]  
Refer to the exhibit. Routers A and B are the edge devices at two different sites as shown. If each sites  contains an IPv6 network that must be able to communicate over an IPsec tunnel, which type of  authentication can be in use between the two sites?   

A. Pre-shared key  
B. MDS  
C. CHAP  
D. 802. 1x                

Answer: A                            

---

## Q272
What is the reason to send an EIGRP SIA reply to a peer?   

A. To respond to a query reporting that the prefix has gone stuck-in-active  
B. To respond to an SIA query that the router is still waiting on replies from its peers  
C. To respond to a reply reporting that the prefix has gone stuck-in-active  
D. To respond to an SIA query with the alternative path requested             

Answer: B                                                 

---

## Q273
What can PfR passive monitoring mode measure for UDP flows?   

A. Delay  
B. Throughput  
C. Loss  
D. Reachability          

Answer: B                                                 

---

## Q274
Drag and drop each description from the left into the matching protocol category on the right      
![exhibit][q274]

Answer:                   
![exhibit][q274a]

---

## Q275
![exhibit][q275]  
Refer to the exhibit. If R1 contacts the RADIUS server but is unable to find the user name in the server  database, how will it respond?   

A. It will attempt to contact TACACS+ server  
B. It will attempt to authenticate the user against the local database  
C. It will prompt the user to enter a new username  
D. It will deny the user access             

Answer: D                                     

---

## Q276
Which two statements about 802. 1Q tunneling are true? (Choose two)   

A. Mac-Based QoS and UDLD are supported on tunnel ports  
B. Its maximum allowable system MTU is 1546 bytes  
C. Traffic that traverses the tunnel is encrypted  
D. The default configuration sends cisco Discovery Protocol, STP, and, VTP information  
E. It is supported on private VLAN ports  
F. It requires a system MTU of at least 1504 bytes       

Answer: A, E                                                 

---

## Q277
What is the initial BFD state?   

A. Up  
B. Down  
C. Init  
D. AdminDown       

Answer: B                                                    

---

## Q278
![exhibit][q278]  
Refer to the exhibit. While troubleshooting a connectivity issue, you executed a traceroute that a returned  the given output. Which conclusion can you draw about the problem?   

A. The PDUs transmitted errors  
B. An ACL is blocking traffic  
C. Packets are being fragmented  
D. The destination is too busy       

Answer: D                                    

---

## Q279
Which statement about Cisco Express Forwarding is true?   

A.The FIB table and the adjacency table reside on the line cards when Cisco Express Forwarding is enabled  
B.The FIB table resides on the route processor and the adjacency table resides on the line cards when Cisco Express Forwarding is enabled  
C.Layer 2 next-hop address information is maintained in the FIB table  
D.Layer 2 next-hop address information is maintained in the adjacency table       

Answer: D                                

---

## Q280
Which three types of behavior does an OSPFv3 Ipv6 AF-capable router exhibit when a non-AF-capable  router attempts to form an adjacency? (Choose three)   

A.Hellos are not allowed  
B.DBDs are honored  
C.LSAs are not honored  
D.LSAs are honored  
E.Hellos are honored  
F.DBDs are not honored         

Answer: C, E, F                            

---

## Q281
Which three protocols are permitted by IEEE 802. 1x port-based authentication before the client is  successfully authenticated by the RADIUS server? (Choose three)   

A.IP  
B.CDP  
C.EAPOL  
D.STP  
E.BOOTP  
F.TCP           

Answer: B, C, D                          

---

## Q282
![exhibit][q282]  
Refer to the exhibit. Which two statements about the network environment must be true? (Choose two)   

A.If the administrator enters the show ip ospf neighbor GigabitEthernet0/1 command, the output is blank  
B.The applet runs before any command are executed  
C.An OSPF neighbor relationship is reestablished when the interface recovers  
D.The applet runs only after OSPF neighbors are verified  
E.A BGP neighbor relationship is established over GigabitEthernet0/1           

Answer: A, B                  

---

## Q283
What are the two Cisco recommended methods for reducing the size of the TCAM on a Layer 3 switch?  (Choose two)   

A.Use the ip route profile command  
B.Filter unwanted routes  
C.Adjust the output queue buffers  
D.Optimize the SDM template  
E.Use summary routes           

Answer: B, E                            

---

## Q284
What are two general SDN characteristics? (Choose two)   

A.Northbound interfaces are open interfaces used between the control plane and the data plane  
B.OpenFlow is considered one of the first Northbound APIs used by SDN controllers.  
C.The separation of the control plane from the data plane  
D.Southbound interfaces are interfaces used between use control plane and the data plane  
E.OVSDB is an application database management protocol         

Answer: A, C                                

---

## Q286
What command can you enter to configure NBAR to recognize VNC traffic?   

A.Ip nbar application-map VNC udp 5900 5901  
B.Ip nbar port-map VNC hex 0xAA 0x1B  
C.Ip nbar port-map VNC tcp 5900 5901  
D.Ip nbar custom-map VNC tcp-udp 5900 5901  
E.Ip nbar port-to-application set VNC tcp 5900 5901           

Answer: C                              

## Q287
Which two statements correctly describe IGMP filtering? (Choose two)   

A.It enables a device to function as a multicast endpoint  
B.It forwards IGMP reports to the upstream multicast router to support source-base filtering  
C.It can designate a port as a multicast host port instead of a multicast router port  
D.It requires IGMP snooping to be enabled  
E.It controls the way in which multicast traffic can access a port  
F.It filters IGMP membership reports and queries         

Answer: D, F                              

---

## Q288
What is one requirement to support the IGMP proxy feature?   

A.Devices connected to a unidirectional link must disable Internet access  
B.PIM-DM must be enabled on all unidirectional links  
C.Device on the unidirectional link must be in the same IP subnet  
D.IGMP snooping must be disabled     

Answer: C                                    

---

## Q289
Which three pieces of information are carried in OSPF type-3 LSAs? (Choose three)   

A.Authentication type  
B.External route tag  
C.Forwarding address  
D.Subnet mask  
E.Metric  
F.IP subnet      

Answer: D, E, C                                 

---

## Q290
Which two items must be defined to capture packet data with the Embedded Packet Capture feature?  (Choose two)   

A.The capture buffer  
B.The capture rate  
C.The capture point  
D.The capture file export location  
E.The capture filter  
F.The buffer memory size           

Answer: A, F                          

---

## Q291
Which three basics types of SD-WAN deployment are out on the market? (Choose three)   

A.Managed service SD-WAN  
B.Policy-Based SD-WAN  
C.SD-WAN as-a-Service  
D.Internet-Based SD-WAN  
E.Secure SD-WAN service  
F.MPLS-based      

Answer: C, D, E                                  

---

## Q292
![exhibit][q292]
Refer to the exhibit. If A DHCP server has generated the given debug output, which two statements about  the network environment must be true? (Choose two)   

A.The DHCP server received a DHCPREQUEST from a client whose ID ends in 4574.3021.30  
B.The DHCP pool for the 10.10.2.0/24 subnet is configured incorrectly  
C.Client 0050.4332 has been assigned an IP address on the 10.10.2.0/24 subnet  
D.The DHCP server receives discover messages through a relay agent  
E.The DHCP server assigned PC2 an address from the 10.10.3.0/24 subnet       

Answer: C, D              

---

## Q293
Which two conditions must be met before IS-IS Level 1 routers will become adjacent? (Choose two)   

A.The routers must be in different areas  
B.The routers must be in the same area  
C.The routers must share a common process ID  
D.The routers must share a common Autonomous System Number  
E.The router must share a common network segment  
F.The routers must be configured with the neighbor command     

Answer: B, E                                   

## Q294
![exhibit][q294]  
Refer to the exhibit. If a Layer 3 switch running OSPF in a VRF-lite configuration reports this error, which  action can you take to correct the problem?   

A. Set mls cef maximum-routes in the global configuration   
B. Configure the control plane with a larger memory allocation to support the Cisco Express Forwarding  Information Base  
C. Upgrade the Layer 3 switch to a model that to a model that can support more routes  
D. Add the vrf-lite capability to the OSPF configuration         

Answer: A                                        

---

## Q295
![exhibit][q295]  
Refer to the exhibit. Router A is connected as a BGP neighbor to routers B and C Which path does router A  use to get to AS 65010?   

A. Through router B because it has the shortest AS Path  
B. Through router C because it has higher local preference   
C. Through router B because the default local preference is 500 and higher than router C   
D. Will load balance both because routers have a same Med value             

Answer: A                            

---

## Q296
Drag each routing Protocol on the left to the matching statement on the right      
![exhibit][q296]  

Answer:   CDR IS-IS, EIGRP,OSPF,BGP,RIP                                        

---

## Q297
Drag and drop each IS-IS router type from the left onto the best matching OSPF router type on the right      
![exhibit][q297]  

Answer:                                                                                   
![exhibit][q297a]  

---

## Q298
Which two statements about HDLC are true? (Choose two)  

A. The packet header contains the control field and address  
B. It supports clear-text authentication  
C. It is a frame-oriented data link layer protocol  
D. It guarantees error-free transmission  
E. It supports both synchronous and asynchronous serial links  

Answer: A, E

---

## Q299
Which two circumstances can cause unicast flooding? (Choose two)  

A. Multiple STP topology change events  
B. Implementing uRPF on the network  
C. Symmetrical routing  
D. MAC table overflow  
E. Multiple broadcast frames  

Answer: B, D


[q2]: exhibits/q2.jpg "Q2 exhibit"
[q6]: exhibits/q6.jpg "Q6 exhibit"
[q10]: exhibits/q10.jpg "Q10 exhibit"
[q16]: exhibits/q16.jpg "Q16 exhibit"
[q17]: exhibits/q17.jpg "Q17 exhibit"
[q12]: exhibits/q12.jpg "Q12 exhibit"
[q18]: exhibits/q18.jpg "Q18 exhibit"
[q21]: exhibits/q21.jpg "Q21 exhibit"
[q23]: exhibits/q23.jpg "Q23 exhibit"
[q31]: exhibits/q31.jpg "Q31 exhibit"
[q33]: exhibits/q33.jpg "Q33 exhibit"
[q36]: exhibits/q36.jpg "Q36 exhibit"
[q40]: exhibits/q40.jpg "Q40 exhibit"
[q43]: exhibits/q43.jpg "Q43 exhibit"
[q46]: exhibits/q46.jpg "Q46 exhibit"
[q55]: exhibits/q55.jpg "Q55 exhibit"
[q56]: exhibits/q56.jpg "Q56 exhibit"
[q63]: exhibits/q63.jpg "Q63 exhibit"
[q71]: exhibits/q71.jpg "Q71 exhibit"
[q73]: exhibits/q73.jpg "Q73 exhibit"
[q80]: exhibits/q80.jpg "Q80 exhibit"
[q89]: exhibits/q89.jpg "Q89 exhibit"
[q107]: exhibits/q107.jpg "Q107 exhibit"
[q108]: exhibits/q108.jpg "Q108 exhibit"
[q109]: exhibits/q109.jpg "Q109 exhibit"
[q110]: exhibits/q110.jpg "Q110 exhibit"
[q113]: exhibits/q113.jpg "Q113 exhibit"
[q115]: exhibits/q115.jpg "Q115 exhibit"
[q116]: exhibits/q116.jpg "Q116 exhibit"
[q123]: exhibits/q123.jpg "Q123 exhibit"
[q127]: exhibits/q127.jpg "Q127 exhibit"
[q131]: exhibits/q131.jpg "Q131 exhibit"
[q132]: exhibits/q132.jpg "Q132 exhibit"
[q136]: exhibits/q136.jpg "Q136 exhibit"
[q137]: exhibits/q137.jpg "Q137 exhibit"
[q138]: exhibits/q138.jpg "Q138 exhibit"
[q140]: exhibits/q140.jpg "Q140 exhibit"
[q144]: exhibits/q144.jpg "Q144 exhibit"
[q145]: exhibits/q145.jpg "Q145 exhibit"
[q147]: exhibits/q147.jpg "Q147 exhibit"
[q148]: exhibits/q148.jpg "Q148 exhibit"
[q149]: exhibits/q149.jpg "Q149 exhibit"
[q150]: exhibits/q150.jpg "Q150 exhibit"
[q153]: exhibits/q153.jpg "Q153 exhibit"
[q156]: exhibits/q156.jpg "Q156 exhibit"
[q157]: exhibits/q157.jpg "Q157 exhibit"
[q160]: exhibits/q160.jpg "Q160 exhibit"
[q166]: exhibits/q166.jpg "Q166 exhibit"
[q170]: exhibits/q170.jpg "Q170 exhibit"
[q177]: exhibits/q177.jpg "Q177 exhibit"
[q178]: exhibits/q178.jpg "Q178 exhibit"
[q179]: exhibits/q179.jpg "Q179 exhibit"
[q180]: exhibits/q180.jpg "Q180 exhibit"
[q190]: exhibits/q190.jpg "Q190 exhibit"
[q191]: exhibits/q191.jpg "Q191 exhibit"
[q204]: exhibits/q204.jpg "Q204 exhibit"
[q216]: exhibits/q216.jpg "Q216 exhibit"
[q224]: exhibits/q224.jpg "Q224 exhibit"
[q230]: exhibits/q230.jpg "Q230 exhibit"
[q235]: exhibits/q235.jpg "Q235 exhibit"
[q236]: exhibits/q236.jpg "Q236 exhibit"
[q238]: exhibits/q238.jpg "Q238 exhibit"
[q242]: exhibits/q242.jpg "Q242 exhibit"
[q245]: exhibits/q245.jpg "Q245 exhibit"
[q248]: exhibits/q248.jpg "Q248 exhibit"
[q251]: exhibits/q251.jpg "Q251 exhibit"
[q24a]: exhibits/q24a.jpg "Q24a Exibit"  
[q24b]: exhibits/q24b.jpg "Q24b Exibit"  
[q24c]: exhibits/q24c.jpg "Q24c Exibit"  
[q24d]: exhibits/q24d.jpg "Q24d Exibit"  
[q55a]: exhibits/q55a.jpg "Q55a Exibit"
[q71a]: exhibits/q71a.jpg "Q71a Exibit"
[q73a]: exhibits/q73a.jpg "Q73a Exibit"
[q132a]: exhibits/q132a.jpg "Q132a Exibit"  
[q132b]: exhibits/q132b.jpg "Q132b Exibit"  
[q132c]: exhibits/q132c.jpg "Q132c Exibit"  
[q132d]: exhibits/q132d.jpg "Q132d Exibit"  
[q132e]: exhibits/q132e.jpg "Q132e Exibit"
[q135]: exhibits/q135.jpg "Q135 Exibit"
[q136a]: exhibits/q136a.jpg "Q136a Exibit"
[q137a]: exhibits/q137a.jpg "Q137a Exibit"
[q138a]: exhibits/q138a.jpg "Q138a Exibit"
[q144a]: exhibits/q144a.jpg "Q144a Exibit"
[q147a]: exhibits/q147a.jpg "Q147a Exibit"
[q148a]: exhibits/q148a.jpg "Q148a Exibit"
[q149a]: exhibits/q149a.jpg "Q149a Exibit"
[q153a]: exhibits/q153a.jpg "Q153a Exibit"
[q156a]: exhibits/q156a.jpg "Q156a Exibit"
[q157a]: exhibits/q157a.jpg "Q157a Exibit"
[q160a]: exhibits/q160a.jpg "Q160a Exibit"
[q170a]: exhibits/q170a.jpg "Q170a Exibit"
[q177a]: exhibits/q177a.jpg "Q177a Exibit"
[q178a]: exhibits/q178a.jpg "Q178a Exibit"
[q190a]: exhibits/q190a.jpg "Q190a Exibit"
[q238a]: exhibits/q238a.jpg "Q238a Exibit"  
[q238b]: exhibits/q238b.jpg "Q238b Exibit"  
[q238c]: exhibits/q238c.jpg "Q238c Exibit"  
[q269]: exhibits/q269.jpg "Q269 Exibit"
[q269a]: exhibits/q269a.jpg "Q269a Exibit"                
[q271]: exhibits/q271.jpg "Q271 Exibit"  
[q274]: exhibits/q274.jpg "Q274 Exibit"
[q274a]: exhibits/q274a.jpg "Q274a Exibit"
[q275]: exhibits/q275.jpg "Q275 Exibit"  
[q278]: exhibits/q278.jpg "Q278 Exibit"  
[q282]: exhibits/q282.jpg "Q282 Exibit"  
[q292]: exhibits/q292.jpg "Q292 Exibit"
[q294]: exhibits/q294.jpg "Q294 Exibit"  
[q295]: exhibits/q295.jpg "Q295 Exibit"  
[q296]: exhibits/q296.jpg "Q296 Exibit"  
[q297]: exhibits/q297.jpg "Q297 Exibit"  
[q297a]: exhibits/q297a.jpg "Q297a Exibit"  
