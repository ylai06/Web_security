# Network Perimeter Defence
Prevent unauthorized access and malicious activities.
網絡邊界防禦，避免未授權的訪問和惡意攻擊。

Examples: Firewalls, Intrusion detection systems(IDS), Intrusion prevention systems(IPS)
## Defense in Depth
Using a layer approach (1) Increases attacker's risk of detection. (2)Decrease attacker's chance of success.
## Perimeter Defence
- Properly configured firewalls and border routers are the cornerstone for Perimeter defence.
- Internet and mobility increase security risk.
- VPN and wireless networks cause the disappearance of traditional concept of network perimeter.
- Most modern attacks occur on Application Layer(OSI).
- Traditional packet-filter firewalls only block (1)Network ports. (2)Computer addresses.
- Client Defence block (1)attack bypass perimeter defence. (2)attack originates from an internet network.
  - Includes: Hardening operating system, Antivirus software, Personal firewalls.
  - Requires configuring many computers.
  - Users may bypass client defence in unmanaged environments.
- Detect common attacks: (1)Records suspicious traffic in event logs. (2)Alert to administrators.
## Firewalls
Regulate and filter network traffic.
- In a simple environment: a packet filtering firewall.
- In complex environments: several firewalls and proxies.
### Types of firewalls:
1. *Packet filtering firewall*: Control data flow to and from a network on the Network Layer(OSI). 
2. *Application-level Gateway(Proxy) firewall*: Filter traffics on the application layer(OSI).
3. *Host-based firewall*: Configue on individual devices, protection at the device level.
4. *Next-generation firewall*: Offer advanced features, such as deep packet inspection, intrusion prevention, and application awareness.
### Deployment strategy
1. Perimeter Firewall
2. Internal Segmentation Firewall(ISFW)
