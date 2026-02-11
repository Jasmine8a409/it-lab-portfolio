# Lab Report — 2.3.2 Lab: Select and Configure Dual Monitors

## General Information
- **Date:** 10/29/2025
- **Platform:** CertMaster
- **Category/Cert:** CompTIA A+ Part 1
- **Video Walkthrough:** [📺 View Dual Monitor Configuration Demonstration](https://youtu.be/JdJYC9RoJCU)

---

## Objectives
* Select and Install a Dual-Output PCIe Video Card
* Establish Power and Multi-Display Connectivity
* Configure Extended Desktop Settings in Windows
* Optimize Monitor Alignment and Primary Display Selection

---

## Environment / Tools
- **OS / Version:** Windows 10 (Simulated)
- **Tools / Hardware:**
    - **Video Card:** PCIe x16 GPU with DVI and HDMI outputs.
    - **Cables:** 1x DVI cable, 1x HDMI cable.
    - **Power:** 6-pin PCIe power supply connector.
    - **Displays:** 2x Desktop Monitors (Marketing Workstation).

---

## Steps (High Level)

1. **GPU Installation & Power:** Selected a PCIe video card capable of supporting dual outputs. Seated the card in the PCIe x16 slot and connected the **6-pin PCIe power connector** from the PSU to ensure the card had sufficient power for creative applications.

2. **Cable Integration:** - Connected the original monitor to the new GPU using the existing **DVI cable**.
   - Connected the second (new) monitor using an **HDMI cable**.

3. **System Initialization:** Powered on the workstation and monitors. Verified that both displays were receiving a signal before proceeding to software configuration.

4. **Display Configuration:** - Opened Windows Display Settings and used the **Identify** tool to label the monitors.
   - Dragged the virtual screen icons to match the physical placement (new monitor on the left).
   - Set the **new monitor as the main display**, ensuring the Start menu and taskbar migrated to the primary creative screen.

---

## Troubleshooting Notes
- **Symptoms:** The second monitor displays "No Signal" after the computer boots.
- **Root Cause:** The display was not set to "Extend" mode in Windows Display Settings, or the input source on the monitor was set to VGA instead of HDMI.
- **Fix & Validation:** Used `Win + P` to select **Extend** mode and toggled the monitor OSD to the HDMI input; the desktop successfully expanded to both screens.

---

## Screenshots
> *Place images in the `/screenshots` folder and reference here.*

---

## What I Learned
- **Power Requirements:** High-performance video cards, even those used for office/marketing work, often require dedicated 6-pin power to stabilize the dual-output signal.
- **Workspace Ergonomics:** I learned the importance of using the **Identify** and **Alignment** tools to ensure the mouse moves seamlessly between monitors without "jumping" vertically.
- **Main Display Logic:** Changing the "Main Display" is critical for user workflow, as it dictates where system notifications and the primary taskbar reside.

---

## Next Time / Variations
- **Resolution Matching:** I would like to practice matching resolutions and refresh rates between two different monitor models to provide a more uniform visual experience for the user.
- **Cable Standards:** Next time, I would explore using two DisplayPort cables to see if the video card supports Daisy Chaining (MST) for an even cleaner cable setup.
