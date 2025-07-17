# Project Home Network – Structured Cabling and Wall Plate Installation

This project documents the process of installing structured Ethernet cabling and keystone wall plates to extend wired connectivity throughout the home. The goal was to provide fast and stable LAN access across multiple rooms using existing wall conduits.

---

## Objectives

- Extend Ethernet access to multiple rooms using wall plates
- Reuse existing satellite cable conduits to run Cat6 cable
- Terminate cleanly with keystone jacks and RJ45 plugs
- Validate with tester and real-world speed tests

---

## Tools and Materials Used

- Cat6 Ethernet bulk cable
- RJ45 plugs and Cat6 keystone jacks
- Wall plate mounting brackets
- Punchdown tool
- RJ45 crimper and cable stripper
- Ethernet cable tester
- USB-C to Gigabit Ethernet adapter (for speed tests)
- **UGREEN 5-Port Gigabit Ethernet Switch** (Unmanaged)
- **5G router** – providing uplink to the switch

---

## Conduit and Cabling Notes

- **Wiring standard:** T568B on all terminations
- Cables routed through existing **satellite TV conduits** (Arabic: *qassam*, i.e., junction box), avoiding new drilling
- Room ends terminated with RJ45 plugs; wall outlets terminated with keystone jacks

---

## Installation and Testing Steps

1. Pulled cable through the junction boxes and wall conduits
2. Crimped room-side RJ45 plugs
3. Punched down wall-side keystone jacks and installed plates
4. Verified pinouts using Ethernet cable tester
5. Connected all drops to **UGREEN unmanaged switch**
6. Uplinked switch to 5G router
7. Validated performance via real-world speed tests from each room

---

## Troubleshooting and Lessons Learned

- **Pin 2 missing**: traced to misaligned crimp; fixed by re-crimping plug
- **Loose pin 5**: resolved by reseating punchdown at the keystone
- **Second wall plate**: multiple pin failures, all resolved by redoing both ends
- **Lesson:** Cable tester is essential before mounting plates

---

## Final Results

- All installed wall plates passed tester validation
- Clean signal across all lines; no loose pins or miswires
- Achieved **~220 Mbps download / 14 Mbps upload** from Room 4 via phone adapter
- Neatly centralized at stairwell junction with visible switch layout

---

## Photos

1. **Initial cable prep and conduit routing**  
   ![](images/20250517_174527.jpg)

2. **Punching down Cat6 cable into keystone jack**  
   *(Strain relief boot visible — can't remember why it was added here)*  
   ![](images/20250517_175530.jpg)

3. **Testing keystone wiring using Ethernet cable tester**  
   ![](images/20250517_192301.jpg)

4. **Close-up view of keystone punchdown**  
   ![](images/20250518_031028.jpg)

5. **Crimping RJ45 plug for device-side termination**  
   ![](images/20250518_031131.jpg)

6. **RJ45 plug alignment before crimp**  
   ![](images/20250518_031323.jpg)

7. **Final visual inspection before mounting wall plate**  
   ![](images/20250518_031449.jpg)

8. **Completed keystone snapped into wall plate**  
   ![](images/20250518_031457.jpg)

9. **Testing wall-mounted port with Ethernet cable tester**  
   ![](images/20250518_051442.jpg)

10. **Wall plate fully mounted and finished**  
    ![](images/20250518_052810.jpg)

11. **Speedtest result via phone with USB-C Ethernet adapter**  
    ![](images/Screenshot_20250518_052729_Speedtest.jpg)

12. **Main terminal: UGREEN unmanaged switch mounted at junction box**  
    ![](images/20250717_062802.jpg)
