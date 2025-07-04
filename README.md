Home Network Lab
This project is a basic Cisco networking simulation built using Cisco Packet Tracer. It demonstrates how to configure a small local area network (LAN) using a Router (1841), Switch (2960), and two PCs.

📁 Project Files
Packet Tracer Simulation File (.pkt)
Screenshots (connection and configuration steps)
🖥️ Devices Used
1 Router: Cisco 1841
1 Switch: Cisco 2960-24TT
2 PCs: Generic PC-PT (PC0 and PC1)
🧷 Network Topology
[PC0] ----

[Switch0] ---- [Router0] / [PC1] ----

📡 IP Configuration
Device	IP Address	Subnet Mask	Default Gateway
PC0	192.168.1.10	255.255.255.0	192.168.1.1
PC1	192.168.1.11	255.255.255.0	192.168.1.1
All IP addresses were configured manually on each PC under Desktop > IP Configuration.

🔌 Cabling
Copper Straight-Through cables were used to connect:
Each PC to the Switch
Switch to Router (FastEthernet0/0 on the Router)
🛠️ Configuration Steps (based on screenshots)
1️⃣ Connected PC0 and PC1 to Switch0
Used FastEthernet0/1 and FastEthernet0/2 on Switch
2️⃣ Connected Switch0 to Router0
Router port: FastEthernet0/0
Switch port: FastEthernet0/23
3️⃣ Set IP configuration manually on PCs
Verified connectivity with ping tests.
🧪 Test & Verification
Use the following command in the PC Command Prompt (Desktop > Command Prompt):

ping 192.168.1.11   # From PC0 to PC1
ping 192.168.1.1    # Test router gateway reachability

✅ Outcome
All devices were able to communicate through the configured network.

📸 Screenshots(not in order just a guide)

![-](https://github.com/user-attachments/assets/e440b51d-ed6b-43db-a84b-4a71a6382b93)
![9](https://github.com/user-attachments/assets/866f667c-2919-4934-9f83-46ecff471aa6)
![8](https://github.com/user-attachments/assets/b0d6a011-6e0f-47fc-88c7-515910d48298)
![7](https://github.com/user-attachments/assets/99e7796f-99e5-49e1-ac69-93e3aa1b8ffe)
![6](https://github.com/user-attachments/assets/87cf748a-9989-4e4d-bab4-6548776096c1)
![5](https://github.com/user-attachments/assets/7c77b00b-73a8-46b4-b6ce-3cb5eb1305cf)
![4](https://github.com/user-attachments/assets/3548c8fd-ac8e-4cd5-8f6e-5fc0448259b6)
![3](https://github.com/user-attachments/assets/aa0e8c2f-e75c-4f38-a618-99c6c40e2c62)
![2](https://github.com/user-attachments/assets/ac321acf-25b3-4a5e-84ce-de107721d659)
![1](https://github.com/user-attachments/assets/6c911bd4-7dd2-4d16-b364-da72d9b3c4a0)
![0](https://github.com/user-attachments/assets/e1baea0a-4aba-43f0-b4bf-0a3fa8f9967d)

🧠 Learning Goals
Understand basic LAN topology


Use Cisco 1841 routers and 2960 switches


Practice IP addressing and connectivity testing






📎 Requirements
Cisco Packet Tracer


Made by [Ville Starr]
