# Principles of Network Security
## No1. Defence in Depth
- Definition: "Defence in Depth"(深度防禦) is a network security strategy that aims to improve the overall security of the system by implementing multi-layered security measures at various levels of the network architecture.
- Goal: To deploy multiple security layers at different levels and stages to deal with different types of threats. By establishing a series of defence barriers to slow down and stop attackers, making it difficult for them to damage the network.
- Recognize there is no perfect security measure, organizations can better protect systems and data by layering multiple defences.

## No2. Principle of Least Privilege(PoLP)
- definition: "Principle of Least Privilege"(最小權利原則) access rights given to users, programs, or system components in a system or network should be the least necessary and limited to the minimum necessary to complete their jobs.
- Goal: Reduce potential risks and security vulnerabilities caused by users, applications, or system components having excessive permissions, and limit the impact of potential abuse(濫用), misconfiguration(錯誤配置), or malicious attacks(惡意攻擊).
- Includes the following aspects:
  - *User permissions*: Users are granted only the minimum permissions necessary to perform their jobs and avoid accessing irrelevant sensitive information or system resources.
  - *Application permissions*: Applications should run with least privilege to prevent them from having excessive access to the system.
  - *System component permissions*: System components (such as services, processes, etc.) should also be configured according to the principle of least privilege to limit their access to system resources.

## No3. Separation of Duties(SoD)
- definition: A principle of information security and internal controls used to prevent internal abuse, error, or fraud. In an organization or business, potential risks are reduced by allocating the execution of sensitive tasks to different people or departments.
- Goal: Reduce the potential for abuse of power by ensuring that a particular activity or task is not completely controlled by a single individual.

## No4. Secure by Design
- definition: Emphasis on considering and integrating(集成) security in the early stages of system, application or product design to ensure strong security during implementation and operation phases
- Goal: Prevent potential security vulnerabilities, reduce the attack surface, and improve the overall security of the system.

* Never be an afterthought
* Need to be designed from start to finish
* Should have security OOBT(Out of The Box): 在產品、系統或服務交付時即具備初始的安全性配置和措施。強調在設計和開發階段將基本的安全性整合到產品中，以降低使用者或組織在部署和使用過程中可能遇到的風險。

## No5. Keep it Simple Stupid(KISS)
- definition: keep it simple and avoid using overly complex code when developing or designing.
- Goal: To make software easy to understand and maintain, and to reduce errors in software. The key point to increase system quality.
- Approach:
  1. Evaluate the functions required by the system and remove redundant or unnecessary functions.
  2. If you have to choose between two solutions, choose the simpler one.

## No?. Security by obscurity
- Definition: "Security by Obscurity"(匿名安全) is a security practice in which security relies on the confidentiality of information, systems, or applications rather than on a public, widely auditable security design.
- Approach/Goal: Hiding critical information, configurations, or algorithms to make it more difficult for attackers to discover and exploit potential vulnerabilities. However, "Security by Obscurity" is often considered an insufficient primary security measure and should not be the only security strategy.

### Kerckhoff's Principle
- Definition: A cryptographic system should be designed to be secure, even if all its details, except for the key, are public known. A good cryptographic system should meet the following conditions:
  1. The security of the algorithm should not depend on the confidentiality of the algorithm itself. Even if the attacker knows all the details of the algorithm, the system should still be safe.
  2. The key is the only information in the system that needs to be kept secret.

### Shannon's Maxim
- Definition: The design of the system should be based on the confidentiality of the key which assumes that the attacker has already know complete knowledge(including the algorithms and protocols) of the system.

### Summary
Both principles emphasize the importance of transparency and reliance on keys for system security. In cryptography, open design and transparent review of algorithms help uncover potential vulnerabilities(發現潛在的漏洞), and the security of a system is built on the confidentiality of keys.



