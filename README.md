# 🌐 VLAN – Access & Trunk Ports | Cisco Packet Tracer

## 📌 Project Overview

This project demonstrates a simple network scenario where the **same department is located on different floors** of a building.

Each floor has its own switch, and the same department is assigned to the **same VLAN** on both switches. A **Trunk Port** is used between the switches to carry the VLAN traffic between floors.

```text
🏢 Floor 1                         🏢 Floor 2

💻 PC ── Access ── SW1 ═══ 🔀 ═══ SW2 ── Access ── 💻 PC
          VLAN 10       Trunk       VLAN 10
             └────── Same Department ──────┘
```

> 💡 The same VLAN ID must be configured on both switches, and the trunk must carry that VLAN.

---

## 🏗️ Network Architecture

### 📍 Network Architecture

<p align="center">
  <img width="700" alt="Network Architecture" src="https://github.com/user-attachments/assets/5312b291-4827-409c-a62c-9501a5416cab" />
</p>


### 🖥️ Cisco Packet Tracer
<p align="center">
<img width="614" height="320" alt="image" src="https://github.com/user-attachments/assets/d68ef178-1a79-469e-a91c-27fb26729b5b" />
</p>

---

## 🔌 Access Port vs 🔀 Trunk Port

|         | 🔌 Access Port       | 🔀 Trunk Port            |
| ------- | -------------------- | ------------------------ |
| Purpose | Connects end devices | Connects network devices |
| VLANs   | One VLAN             | Multiple VLANs           |
| Example | PC → Switch          | Switch → Switch          |

**In simple terms:**

🔌 **Access Port → connects a device to a VLAN**

🔀 **Trunk Port → carries multiple VLANs between switches**

---

## 🎯 Objectives

* 🏷️ Understand VLANs
* 🔌 Understand Access Ports
* 🔀 Understand Trunk Ports
* 🏢 Connect the same department across different floors
* 🧪 Verify connectivity using Cisco Packet Tracer

---

## 🛠️ Tools

* 🌐 Cisco Packet Tracer
* 🔀 Cisco Switches
* 💻 PCs
* 🏷️ VLANs
* 🔌 Access & Trunk Ports

---

## 🚀 Conclusion

This lab provides a practical demonstration of **VLANs, Access Ports, and Trunk Ports**, with a focus on understanding how the same department can communicate across different floors using the same VLAN.
