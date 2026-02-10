# Lab Report — 2.1.7 Lab: Install USB Devices

## General Information
- **Date:** 10/29/2025
- **Platform:** CertMaster
- **Category/Cert:** CompTIA A+ Part 1
- **Activity:** New Computer Installation (Corporate Office)
- **Video Reference:** [▶️ Click here to watch the Lab Walkthrough]https://www.youtube.com/watch?v=QezgJi0-tuA)

---

## Objectives
* Establish Workspace Power Distribution
* Integrate Input, Output, and Specialized Peripherals
* Configure Wired Network Connectivity
* Perform Initial System Power-On and Validation

---

## Environment / Tools
- **OS / Version:** Windows 10 (Simulated)
- **Tools / Hardware:**
    - Power Distribution: Wall outlet, Power strip (Surge protector)
    - Input: USB Keyboard, USB Mouse
    - Output: 3.5mm Analog Speakers, HDMI/DP Monitor
    - Specialized: Desktop Printer (USB)
    - Connectivity: Cat6 Ethernet Cable (RJ-45)

---

## Steps (High Level)
1. **Power Infrastructure Setup** Connected the power strip directly to the wall outlet. This serves as the central power hub for the workstation, monitor, and printer.

2. **Peripheral Integration (On-Bench)**
   Connected the keyboard and mouse to available USB Type-A ports on the computer. Attached the analog speakers to the lime-green 3.5mm jack. Added the monitor and printer to the workspace, connecting them to the PC via video and USB cables, respectively.



3. **Power Distribution**
   Plugged the power cables for the Computer (PSU), Monitor, and Printer into the power strip to ensure all devices are grounded and powered.

4. **Network Configuration**
   Connected a standard Ethernet cable (RJ-45) from the computer's Network Interface Card (NIC) to the designated network wall plate to establish a wired LAN connection.

5. **Validation**
   Toggled the power strip to the "On" position. Powered on the monitor first, followed by the computer system. Observed the boot sequence to verify that the OS loaded successfully.

---

## Troubleshooting Notes
- **Symptoms:** The printer is not appearing as "Ready" in the operating system despite being plugged into the computer.
- **Root Cause:** The printer was connected via USB, but its independent power cable was not plugged into the power strip.
- **Fix & Validation:** Connected the printer's power cord to the surge protector and cycled the printer's power button; the OS immediately recognized the device.

---

## Screenshots
> ![Install USB Devices Lab Screenshot](<../Cables and Connectors/2.1.7 Lab Install USB Devices Screenshot.png>)

---

## What I Learned
- **Workflow Efficiency:** I learned that setting up the power infrastructure first (the power strip) makes managing multiple device cables much cleaner than trying to reach for the wall outlet repeatedly.
- **Cable Identification:** Practiced distinguishing between the network port (RJ-45) and older phone ports (RJ-11) to ensure proper internet connectivity.

---

## Next Time / Variations
- **Cable Management:** I would like to use cable sleeves to bundle the monitor, printer, and power cables together for a more professional "corporate" look. I will note which cable goes where when I unplug them.
- **Dual Monitor Setup:** I'd like to attempt connecting a second monitor to practice configuring "Extended Desktop" mode within the Windows Display Settings.
