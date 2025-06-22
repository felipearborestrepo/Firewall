# 🔥 Firewall Fundamentals Project (Windows & Network Security)

---

## 1. 🔐 What Is a Firewall?
A firewall is a security system that monitors and controls incoming and outgoing network traffic. It acts like a security guard between your computer/network and the internet. You can allow or block data packets based on security rules.

---

## 2. 🧱 Types of Firewalls

- **Stateless Firewall**: Only checks packet headers, not state of connection.
- **Stateful Inspection Firewall**: Tracks the state of connections (more secure).
- **Proxy Firewall**: Uses an intermediary server to filter traffic.
- **Next-Generation Firewall (NGFW)**: Includes deep packet inspection, intrusion prevention, and app awareness.

![Screenshot 2025-06-22 130209](https://github.com/user-attachments/assets/848f94bd-69f0-47cb-8abe-a4fb8bf46c1a)

---

## 3. 🔥 How Firewalls Control Traffic

Traffic flows are filtered based on rules:
- ✅ **Allowed**: Green arrows
- ❌ **Blocked**: Red arrows

![Screenshot 2025-06-22 130101](https://github.com/user-attachments/assets/15d0b6c8-7ce3-49f0-9d60-e6a41fcbdefe)

---

## 4. ✅ Managing Allowed Apps

You can allow or disallow apps from communicating through the firewall here. For example, you might allow your browser or block a risky app.

![Screenshot 2025-06-22 131759](https://github.com/user-attachments/assets/a6540a22-ea1e-4c96-a4b2-de700ccc174f)

---

## 5. 🌐 Firewall Settings Per Network

You can:
- Turn firewall **on or off** for each network profile (Private/Public).
- Block **all incoming connections** on selected profiles.

![Screenshot 2025-06-22 131933](https://github.com/user-attachments/assets/65db35f8-da95-4fc9-b2dd-75e881b54774)

---

## 6. ♻️ Resetting Firewall Settings

Restore all firewall settings to default with one click.

![Screenshot 2025-06-22 132228](https://github.com/user-attachments/assets/b2cb2fec-ba67-41a6-b241-5173e5477747)

---

## 7. 🧭 Visual: Windows Firewall Rule Wizard Pages Explained

This part is to demonstrate how to block outbound traffics from the web server
I was able to connect to this IP address in the web
![Screenshot 2025-06-22 132336](https://github.com/user-attachments/assets/8f8f255f-9334-495a-8047-0835ad78cc14)

### Rule Type
Create custom, program, port, or predefined rules.

![Screenshot 2025-06-22 132459](https://github.com/user-attachments/assets/d84feb15-9f28-452c-95c0-644e589df285)


### Program
Apply rule to all programs or specify one.

![Screenshot 2025-06-22 132521](https://github.com/user-attachments/assets/f2ebf5aa-cf37-42ce-9958-cebaf37b142a)

### Protocol and Ports
Configure TCP/UDP and set specific ports.

![Screenshot 2025-06-22 132558](https://github.com/user-attachments/assets/d4326b5a-158c-4f50-85ab-86fa5a727396)

### Scope
Select IP ranges the rule applies to.

![Screenshot 2025-06-22 132646](https://github.com/user-attachments/assets/73d38340-d8a9-41fd-96d0-368204dcb277)

### Action
Choose to allow or block connections.

![Screenshot 2025-06-22 132650](https://github.com/user-attachments/assets/1328c810-be1f-417e-ac54-4fd8f9f843f9)

### Profile
Decide if the rule applies to Domain, Private, or Public networks.

![Screenshot 2025-06-22 132708](https://github.com/user-attachments/assets/ac122b24-bb91-4508-848f-78fc6f112eef)

---

## 8. 🚫 Practical Example: Blocking Specific Ports (TCP/80 & 443)

### Creating the Rule
Steps:
1. Open **Windows Defender Firewall with Advanced Security**
2. Go to **Outbound Rules > New Rule > Custom**
3. Program: **All programs**
4. Protocol: **TCP**
5. Remote Ports: **80, 443**
6. Action: **Block the connection**
7. Profile: **All**
8. Name: `Block 80, 443 traffic`

![Screenshot 2025-06-22 132734](https://github.com/user-attachments/assets/1c47a7d8-db40-4379-b2a9-b6a8118a2a19)

### Result
Attempting to access a web page now results in a blocked message, confirming the firewall is successfully restricting web traffic.

![Screenshot 2025-06-22 132758](https://github.com/user-attachments/assets/dea63bc3-383b-421e-91e6-2b36332224e5)

---

## 9. 🧠 Why Firewalls Matter

Firewalls:
- 🛡️ Stop unauthorized access
- 🕵️‍♂️ Protect against malware and network threats
- ⚙️ Enforce security rules across applications
- 🌐 Help manage internet access and compliance

---

**✅ Built by:** *[Your Name]*  
Demonstrating real-world Windows firewall management skills for IT support and security roles.

