# Active Directory Lab

## Objective


The Active Directory Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned


- Advanced understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used


- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps

*Ref 1: Network Diagram displaying the flow of data*   <img width="960" alt="Screenshot 2025-01-19 201901" src="https://github.com/user-attachments/assets/11975f51-63f1-4113-baca-b29e732bad5a" />

*Ref 2: Target Machine Setup* <img alt="Screenshot 2025-01-19 205521" src="https://github.com/user-attachments/assets/31ff8e61-564d-4f64-936a-0ab67e826ad1" />

*Ref 3: Domain Controller Setup* <img alt="Screenshot 2025-01-19 211119" src="https://github.com/user-attachments/assets/613a39ab-2d4c-49f6-a9a3-0addd9f7b0ac" />

*Ref 4: Splunk Server Setup* <img alt="Screenshot 2025-01-19 212229" src="https://github.com/user-attachments/assets/98cd1159-8a77-4d91-928d-214d86a554ee" />

*Ref 5: Attacker Machine Setup* <img alt="Screenshot 2025-01-19 212321" src="https://github.com/user-attachments/assets/7c2d5e30-08dc-4d3c-8e93-c31d97b9e534" />

*Ref 6: Configure the Static IP Adress for Splunk Server* <img alt="VirtualBox_splunk_19_01_2025_22_10_04" src="https://github.com/user-attachments/assets/e0971e05-cebd-43cf-a43d-ecb667d8e77c" />

*Ref 7: Configure the Static IP Adress for Target Machine* <img alt="VirtualBox_demo_19_01_2025_22_27_41" src="https://github.com/user-attachments/assets/c2f1bb73-4f23-4728-93b6-bb7a8bf328aa" />
*Ref 8: Our Splunk Universal Forwarder Input Configuration File:                                                                                                               
It will push event logs from Application, Security, System, and Sysmon over to our Splunk Server* <img alt="VirtualBox_demo_19_01_2025_22_42_32" src="https://github.com/user-attachments/assets/2eb9e81c-444a-4115-98ae-fa1fedc0f899" />

*Ref 9: Configure the IP Adress for our Kali Linux Attacker Machine* <img alt="VirtualBox_kali-linux-2024 2-virtualbox-amd64_19_01_2025_23_57_40" src="https://github.com/user-attachments/assets/7ffe3e0f-3182-4ad8-8cdf-17c5c8d0e972" />

*Ref 10: Install Crowbar to use for brute force attack* <img alt="VirtualBox_kali-linux-2024 2-virtualbox-amd64_20_01_2025_00_01_55" src="https://github.com/user-attachments/assets/f677cd45-fe18-45a6-a12b-86b9bb88afec" />


*Ref 11: Run Crowbar Password Command to Attack our Target Machine* <img alt="VirtualBox_kali-linux-2024 2-virtualbox-amd64_20_01_2025_00_35_57" src="https://github.com/user-attachments/assets/b3a503c2-a58c-40a3-8718-7d50d7dc984b" />





