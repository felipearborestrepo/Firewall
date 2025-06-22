# 🔥 Firewall Fundamentals Project (Windows & Network Security)

## 1. 🔐 What Is a Firewall?

A firewall is a security system that monitors and controls incoming and outgoing traffic. It allows or blocks connections based on predefined rules.

![image](https://github.com/user-attachments/assets/d0d7da34-7d72-44e0-8f9a-9994882c91b8)

---

## 2. 🧱 Types of Firewalls

- **Stateless Firewall**: Checks each packet individually.
- **Stateful Inspection Firewall**: Tracks connection state.
- **Proxy Firewall**: Uses an intermediary server.
- **Next-Gen Firewall (NGFW)**: Includes app control & threat prevention.

![Screenshot 2025-06-22 130209](https://github.com/user-attachments/assets/5c47bbab-271c-40eb-8cb5-62ab169bacda)

---

## 3. 🔥 How Firewalls Control Traffic

Traffic flows are filtered based on rules:
- ✅ **Allowed**: Green arrows
- ❌ **Blocked**: Red arrows

![Screenshot 2025-06-22 130101](https://github.com/user-attachments/assets/0e63c2e8-d6be-4006-b3eb-0d606e676362)

---

## 4. ⚙️ Creating a Custom Outbound Rule

Go to **Windows Defender Firewall with Advanced Security**, select **Outbound Rules > New Rule** > choose **Custom**.

<!-- Screenshot 03: Rule Type - Custom -->

Then choose to apply the rule to all programs.

<!-- Screenshot 04: Program - All programs -->

---

## 5. 🚫 Blocking Specific Ports (TCP 80 & 443)

- **Protocol**: TCP  
- **Remote Ports**: 80, 443  
Blocks HTTP/HTTPS traffic.

<!-- Screenshot 05: Protocol & Ports TCP 80, 443 -->

Set the **Scope** to apply to any IP addresses.

<!-- Screenshot 06: Scope - Any IP -->

Set the **Action** to “Block the connection.”

<!-- Screenshot 07: Action - Block the connection -->

Choose to apply the rule to all profiles (Domain, Private, Public).

<!-- Screenshot 08: Profile - All selected -->

Give the rule a name like `Block 80, 443 traffic`.

<!-- Screenshot 09: Rule created successfully (shows rule list) -->

---

## 6. ✅ Managing Allowed Apps

Here you control which apps can pass through the firewall.

<!-- Screenshot 10: Allowed apps and features -->

---

## 7. 🌐 Firewall Settings Per Network

Customize how the firewall behaves on private vs public networks.

<!-- Screenshot 11: Customize network settings -->

---

## 8. ♻️ Resetting Firewall Settings

Easily restore all firewall rules to default.

<!-- Screenshot 12: Restore defaults screen -->

---

## 9. 🌍 Connection Success vs Blocked

Before the rule was added, the connection worked.

<!-- Screenshot 13: Connected Successfully to 10.10.10.10 -->

After blocking port 80/443, the site becomes unreachable.

<!-- Screenshot 14: Can't reach this page (blocked) -->

---

## 10. 🛠 Firewall Rule Wizard - Full Steps

1. **Rule Type** → Custom  
2. **Program** → All programs  
3. **Protocol and Ports** → TCP, ports 80 and 443  
4. **Scope** → Any IP  
5. **Action** → Block the connection  
6. **Profile** → Domain, Private, Public  
7. **Name** → `Block 80, 443 traffic`

---

## 11. 🧠 Why Firewalls Matter

- 🛡️ Protect against intrusions  
- 🌐 Control internet access  
- 🕵️‍♂️ Monitor unauthorized connections  
- 🔐 Essential for both home and enterprise security

---

## 📷 Screenshot List & Upload Suggestions


---

✅ **Done by:** *[Your Name]*  
🧠 *Demonstrating real-world firewall knowledge in Windows environments*
