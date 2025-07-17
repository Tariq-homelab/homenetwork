# Home Ethernet Network Upgrade

This project documents the process of upgrading a home's internal Ethernet wiring using repurposed satellite conduits, wall-mounted keystone jacks, and an unmanaged switch. The goal was to restore reliable wired connectivity across multiple rooms and validate performance through testing.

---

## Project Summary

- **Objective:** Extend wired network access using CAT6 cabling and RJ45 wall plates.
- **Conduit:** Legacy coaxial conduit routed to a central junction.
- **Switch:** UGREEN 5-Port Gigabit Unmanaged Switch (uplinked to a 5G router).
- **Cable Type:** CAT6 UTP.
- **Termination:** RJ45 plug (device side) and punch-down keystone jack (wall side).
- **Validation:** Cable tester and Ethernet speed tests via USB-C adapter on mobile.

---

## Photo Log

### 1. Removal of Old Wall Plate
![1-remove old plate](images/1-remove%20old%20plate.jpg)  
Old faceplate removed to expose legacy coaxial conduit reused for Ethernet routing.

---

### 2. Keystone and Wall Plate Preparation
![2-showcase of wallplate and keystone](images/2-showcase%20of%20wallplate%20and%20keystone.jpg)  
CAT6-compatible keystone jack aligned with modular wall plate for clean in-wall Ethernet termination.

---

### 3. Pair Separation and T568B Positioning
![3-preparing for punch down](images/3-preparing%20for%20punch%20down.jpg)  
Twisted pairs untwisted and positioned according to T568B wiring standard in preparation for termination.

---

### 4. Punch-Down Termination
![4-punch-down](images/4-punch-down.jpg)  
Conductors punched down securely using proper tool.  
*Note: RJ45 rubber boot visible—purpose unclear during this stage.*

---

### 5. Keystone Connected to Wall Plate
![5-keystone connected to wallplate](images/5-keystone%20connected%20to%20wallplate.jpg)  
Fully terminated keystone clipped into the wall plate assembly.

---

### 6. Wall Plate Installed into Junction Box
![6-installation of wallplate](images/6-installation%20of%20wallplate.jpg)  
Wall plate secured onto the junction box. Drywall marks from prior installations remain visible.

---

### 7. Final Installation View
![7-final wallplate state](images/7-final%20wallplate%20state.jpg)  
Completed and operational wall-mounted Ethernet port.

---

### 8. Ethernet Drops Connected to Switch
![8-unmanaged-switch-cable-drop](images/8-unmanaged-switch-cable-drop.jpg)  
All room drops converge at a central junction box patched into a UGREEN unmanaged switch, uplinked to the main router.

---

### 9. Custom Patch Cable Fabrication
![9-patch cable created for testing](images/9-patch%20cable%20created%20for%20testing.jpg)  
RJ45 plug crimped using T568B pinout, tested for continuity. Used for endpoint testing.

---

### 10. USB-C Ethernet Adapter Test Setup
![10-patch cable connected to ethernet to usb c for phone speed test](images/10-patch%20cable%20connected%20to%20ethernet%20to%20usb%20c%20for%20phone%20speed%20test.jpg)  
Smartphone connected via USB-C to Ethernet adapter using the completed Ethernet run.

---

### 11–12. Speed Test Results (Phone via Ethernet)
![11-speedtest1](images/11-speedtest1.jpg)  
![12-speedtest2](images/12-speedtest2.jpg)  
Real-world benchmarks show consistent 200+ Mbps throughput, validating the Ethernet connection.

---

## Tools Used

- RJ45 crimping tool  
- Punch-down tool  
- Wire stripper  
- Wall plates + keystone jacks  
- Ethernet cable tester  
- USB-C to Ethernet adapter  
- Smartphone (testing endpoint)

---

## Notes

- No additional wall drilling was required; existing coaxial conduits were repurposed.
- DHCP reservations planned for consistent network addressing.
- Successful validation through wired benchmarks confirms stable drop performance.
