# Class-D-Switching-Amplifier

This project is a **compact, efficient, and high-fidelity amplifier** designed for digital audio sources and musical instruments like electric guitars or keyboards. It boosts low-level signals to a level suitable for driving speakers or headphones with minimal distortion and high power efficiency.

**📌 Features**

- ✅ **Op-Amp Based Pre-Amplification** (LM386)
- ✅ **Compatible with Guitars, Mobile Phones, Laptops**
- ✅ **Compact PCB Design for Portability**
- ✅ **Low Power Consumption (Battery/USB Powered)**

# Components Used
1. NE555 Timer - 1
2. LM393 Comparator - 1
3. LM386 Audio Amplifier - 1
4. IRF540 NMOS - 2
5. IR2110 MOSFET driver - 1
6. 10k resistor - 3
7. 2.2k resistor - 1
8. 10ohm resistor - 2
9. 10k trim POT - 1
10. UF4007 diode - 3
11. LM7805 - 1
12. LM7812 - 1
13. 102 pF Capacitor - 1
14. 103 pF Capacitor - 1
15. 104 pF Capacitor - 2
16. 22uF Capacitor - 2
17. 470uf Capacitor - 1
18. 1uf Ceramic Capacitor - 2
19. 47uh inductor - 1
20. 3.5mm headphone jack - 1

# Circuit Diagram
[Schematic.pdf](https://github.com/user-attachments/files/19834556/Schematic.pdf)

**Note**: Add a pull-down resistor(10k) to the LM386 output to reduce Noise when no audio is played.
          Also, ensure you're using a 1uf or higher ceramic capacitor for Bootstrapping for proper gate voltage to the high-side MOSFET.

