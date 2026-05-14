The installer for **InOS** is driven by the **Smart System Layer**, which acts as the "Installer Brain" to ensure the OS fits the specific hardware it is being loaded onto. 

### **The Smart System Layer (Installer Brain)**
During the installation process, this layer performs several intelligent actions:
*   **Hardware Detection:** It automatically scans the device to detect its hardware strength and capabilities.
*   **Profile Assignment:** Based on the scan, it assigns a specific **Install Type** and configures system defaults.
*   **Bloatware Removal:** To keep the system lightweight, it proactively removes unnecessary packages that aren't suited for the detected hardware.
*   **Foundation:** Regardless of the type, the system is built on an **Ubuntu minimal foundation** to ensure a stable "engine block".

---

### **Installation Types**
InOS offers two primary installation paths: **Basic** and **Smart OS**.

#### **1. Basic Installation**
This path is simplified into three modes based strictly on general hardware tiers:
*   **Low:** Optimized for low-end or legacy devices.
*   **Medium (Mid):** Designed for most modern, balanced, or generic PCs.
*   **High:** Tailored for advanced performance and gaming rigs.

#### **2. Smart OS Installation**
This is a more granular system that uses **Device Classes** and specific **Levels** to fine-tune the OS:
*   **Mobile (📲):** Levels **0–4** (0 is basic/trash; 4 is advanced/gaming like Redmagic).
*   **Tablet:** Levels **0–4** (0 is trash; 4 is advanced/gaming).
*   **Laptop:** Levels **0–8** (ranging from 0 for low-end, 4 for 2018 hardware, to 8 for advanced gaming).
*   **Desktop:** Levels **0–10** (ranging from 0 for low-end, 6 for 2022 hardware, to 10 for advanced gaming).

---

### **Installer Safety & Recalibration**
A unique feature of the InOS installer is its **Recalibration Safety Feature**. If you later upgrade or change major or minor hardware components (such as a new **CPU or GPU**), the system can recalibrate its levels either **automatically or manually** without requiring a full wipe and reinstall.

### **Software Stack Selection**
The installer chooses the interface based on the assigned hardware level:
*   **Light Builds:** Typically use **XFCE or LXQt** desktop environments to save resources.
*   **High Builds:** Utilize **GNOME or KDE** for a more feature-rich experience.
*   **Boot Visuals:** Even the startup screen adapts, showing a **static logo** for Light builds, a **simple animation** for Mid builds, and a **holo-style effect** for High builds.
