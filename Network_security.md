# Network Security
## Importance of Network Security 
1. **Protection of sensitive data**: Preventing unauthorized access to sensitive information, such as personal data, intellectual property, and financial records, is crucial to protect individuals and organizations from identity theft, financial loss, and reputational damage.
2. **Compliance with regulations**: Many industries, such as healthcare, finance, and government, have strict regulations regarding data protection and privacy. Network security helps organizations comply with these regulations and avoid legal penalties.
3. **Maintaining productivity**: Network security helps ensure the network is available and performs optimally, allowing employees to work efficiently and without disruption.
4. **Building trust**: A secure network fosters trust between an organization and its clients, partners, and employees, as they can be confident that their data is protected.

## Goals of Network Security - CIA
By using the CIA(Model for Network Security), organisations can develop a comprehensive network security system that effectively protects their networks and data from various threats and attackers.

1. **Confidentiality(機密性)**. Such as Encryption, Access control(Authentication, *Authorisation*, Accounting(AAA)), and Network segmentation.
   - *Authentication*: Authorization rules make sure users can only perform what are permitted to do. Such as *DAC for desktops, MAC for Networks, and RBAC for Applications*.
2. **Integrity(完整性)**. Such as Hash, Digital signatures, and *Message Authentication Codes(MAC)*.
   - *MAC*: By using a shared secret key to verify the authenticity and integrity of a message or a piece of data.
3. **Availability(可用性)**. Such as *Redundancy*, *Load balancing*, Disaster recovery planning, and Regular maintenance.
   - *Redundancy(冗余)*: Creating multiple copies of data and systems can help ensure that they remain available even if one component fails.
   - *Load balancing(負載均衡)*: Distributing network traffic across multiple servers can help prevent overloading and ensure that resources are available when needed.

## Threats and Attacks
1. **Threats**: A possible danger that might exploit a vulnerability.
2. **Attacks**: An intelligent act that is a deliberate attempt (Especially in the sense of a method or technique) to evade security services and violate the security policy of a system.

**Threats/Attacks for Passwords**:
1. **Brute force attacks**: An attacker systematically tries different combinations of usernames and passwords to gain unauthorized access to a system.
2. **Password attacks**: Attackers use various techniques, such as dictionary attacks, to crack passwords and gain unauthorized access to systems.
3. **Eavesdropping**: Attackers intercept and monitor network traffic to steal sensitive information.
4. **Social engineering**: Attackers manipulate individuals into divulging sensitive information or performing actions that compromise security. For example: Phishing, Impersonation, Pretexting, social media attacks, etc.

**Threats/Attacks for CIA**:
1. **Confidentiality** (Disclosure of confidential data): Compromising admin-level accounts often results in access to user’s confidential data
2. **Integrity** (Data tampering): Privilege levels do not distinguish users who can only view data and users permitted to modify data.
3. **Availability** (Data destruction): deleting all sensitive information inside a system.

**Threats/Attacks for Transmission**
1. Passive Attacks – Release of message content(Interception), read contents of message from sender.
2. Passive Attacks – Traffic analysis(Interception), observe pattern of message from sender.
3. Active Attacks - Replay(Modification), capture message from sender, later replay to receiver.
4. Active Attacks - Masquerade(偽裝)(fabrication, 偽造), message from hacker that appears to be from sender.
5. Active Attacks - Modification(modification), hacker modifies message from sender to receiver.
6. Active Attacks – Denial of Service(DoS Attack)(Interuption+ Fabrication), hacker disrupts services provided by server.

