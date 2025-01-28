# Personal-SIEM-Project
Creating a SIEM to match my personal cybersecurity needs using Wazuh.

## Objective

This personal SIEM project aimed to create a security measure to monitor my own security environment between two devices. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies. Most importantly, it is also aimed at taking control of my own security. Also special shoutout to MyDFIR on youtube for providing a great tutorial on this specific project.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Risk management
- Threat intelligence and threat driven testing

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Part 1: Planning the SOC Architecture

![image](https://github.com/user-attachments/assets/b0ba5d23-2f13-435d-9504-2a04bcf6f1e4)

*Ref 1: Network Diagram*

This is a high level overview of the dataflow and architecture of the project. Doing this is essential as it provides a clear layout of what you are trying to accomplish with your project. 

## Part 2: Setting up the Environment
I used an Ubuntu server to host my Wazuh manager and other dependencies. This process was straightforward, online materials were enough to help with the setup. 

## Part 3: Tuning the SIEM

## Reflections

Implementing a SIEM on two personal devices can be a great way to learn about different security concepts. Throughout the process security is always something you should always have in mind. Thinking about how threats may look to attack your infrastructure throughout the process should play a role in how to build systems. For example, since you are deploying something on the public cloud, it is critical to configure it's firewall systems accurately to avoid mass scanners and unwanted entities from accessing your wazuh manager page.
