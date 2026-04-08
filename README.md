🔐 SSH Honeypot using Cowrie

📌 Overview

A hands-on cybersecurity project focused on simulating real-world SSH attacks and analyzing attacker behavior using a honeypot.

🎯 Objective

To understand how attackers attempt to gain access to exposed systems and what actions they perform after login.

⚙️ Setup
Deployed Cowrie on Ubuntu (VM)
Configured network using Bridged Adapter
Connected attacker machine (Kali Linux)
Exposed SSH honeypot on port 2222

🧪 Attack Simulation
Performed brute-force SSH attempts from Kali
Tried common usernames and passwords
Observed login attempts and interactions

📊 Key Observations
Frequent login attempts using weak credentials
Repeated username patterns (root, admin, etc.)
Real-time logging of attacker activity

🛠️ Tools & Technologies
Ubuntu
Kali Linux
Cowrie Honeypot
VirtualBox

💡 Use Cases
Beginner cybersecurity project
Understanding attacker behavior
SOC / Blue Team learning

🚀 Future Improvements
Add log visualization (ELK Stack)
Deploy on cloud (AWS)
Automate alerting
