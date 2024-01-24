# Cloud Security Engineering
## The Principles of Network Security
- Security by design(Security in Depth): The implementation of multiple security measures to protect the most valuable resources on your network.
  - **Network Policy**: if you can measure it then it is a network policy. It is a statement that reflects the rules that everyone should abide by. All good policies are organized as follows: Purpose, Policy Compliance, Date Tested, Date Updated, Contact.
  - **Code Practice**: if you’re building something just maintain a good coding practice.
  - **People Guidance**: if you can’t measure it then it is guidance.
    
## How to measure security 
1. The SANS Endpoint Security Maturity Model Curve: Level1(Random or Disorganised)-> Level2(Reactive or Tactical)-> Level3(Preventive)
-> Level4(Organsied or Directed)-> Level5(Proactive, Comprehensive, Continuous and Measurable)   
2. The Cybersecurity Capability Maturity Model (C2M2) maturity indicator levels (MILs)

## Difference between frameworks and models

**framework**: 工具箱\規則
- Definition: A framework is a structured set of concepts, practices, and guidelines that provides a foundation for developing a specific type of system, application, or solution.
- Purpose: Frameworks offer a predefined structure and a set of rules to help developers build applications more efficiently. They provide a foundation that can be customized to meet specific requirements.

**Model**: 表示\概念
- Definition: A model is a simplified representation of a system, process, or concept used to understand, analyze, or communicate its characteristics, behaviours, or structure.
- Purpose: Models help in visualizing and understanding complex systems by breaking them down into simpler, abstract representations. They are used for analysis, communication, and decision-making.

| security frameworks| security models |
|:----:|:----:|
| ISO 27001 | IOT |
| NIST | Blockchain |
| BSI | Could |

**Cyber Security Architect**:
- Role & Mindset(心態)
- Tools
- Domains

## The CIA model
- Confidentiality(保密性): Confidentiality ensures that information can only be accessed by authorized individuals, entities or systems.
- Integrity(完整性): Integrity ensures that information remains accurate, consistent, and untampered with during storage, processing, or transmission.
- Availability(可用性): Availability ensures that information and resources are accessible and available when needed by authorized users.

## The concept of reference diagrams
1. Define Hosts: Host assets are typically equipment that has an operating system and dose not typically include firmware. (Industrial devices excluded)
2. Define Network: Network assets are any assets that enable communication. 
3. Define Stakeholders: Stakeholders are persons involved in the day-to-day operation of the organization.

**Basic**:
- Reuse the diagram
- Illustrate threats
- Show impact on assets
- Show impact on stakeholders
- Manage infrastructure

**Advance**:
- Show forbidden relationships
- Add monitoring nodes
- Identify host assets that needs to stretch
- Identify persistent assets  

## Introduction to Threats and Attacks
**Threat Analysis**: The process of assessing and understanding the impact of potential threats to a system or organization
1. Attack Model-driven(ATT&Ck, Kill chain): Modeling and analysis of possible attacker behavior. It focuses on malicious behaviour, attack paths, and potential motivations of attackers.
2. Compliance Driven (Nist, ISO, BSI): Compliance requirements based on meeting regulations, standards or policies. It is concerned with ensuring that systems comply with specific laws, regulations, or industry standards.



- understand the difference between security policy, coding practice and guidance.
- understand the difference between frameworks and models.
- understand how we can measure security 
- understand the concept of reference diagrams 
