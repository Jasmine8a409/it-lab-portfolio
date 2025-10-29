# A+ — Windows 10 Clean Install (UEFI + GPT)

**Date:** 2025‑10‑29  
**Platform:** TestOut LabSim  
**Video:** (add link)

## Objectives
- Create UEFI boot media, partition GPT, and install Windows 10.
- Apply updates and drivers; validate activation.
- Document post‑install checklist.

## Quick Steps
1. Boot to UEFI USB → `diskpart` → `clean`, `convert gpt`, create primary partition.
2. Install Windows 10 → OOBE → create local admin.
3. Update, drivers, hardening, restore points, imaging.

## Notes
- If boot fails, verify UEFI boot order and Secure Boot.
- Keep screenshots minimal to avoid proprietary content.