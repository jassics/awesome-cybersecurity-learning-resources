# Awesome IoT & Hardware Security Learning Resources

IoT / hardware / embedded security covers firmware analysis, hardware interfaces (UART, JTAG, SWD, SPI, I2C), radio (Bluetooth Low Energy, Zigbee, Z-Wave, LoRa, NFC, SDR), and the growing attack surface of connected devices (smart home, automotive, medical, industrial edge). It overlaps with binary exploitation and reverse engineering.

## ToC
1. [Books](#books)
2. [Videos](#videos)
3. [Free/Paid Courses](#freepaid-courses)
4. [Free/Paid Labs](#freepaid-labs)
5. [IoT / Hardware Tools](#iot--hardware-tools)
6. [Certifications](#certifications)
7. [Blogs/Articles](#blogsarticles)

## Books
1. [Practical IoT Hacking by Fotios Chantzis, Evangelos Deirmentzoglou et al. (No Starch, 2021)](https://nostarch.com/practical-iot-hacking) - The modern standard.
2. [The IoT Hacker's Handbook by Aditya Gupta (Apress)](https://link.springer.com/book/10.1007/978-1-4842-4300-8)
3. [Hardware Hacking Handbook by Jasper van Woudenberg, Colin O'Flynn (No Starch)](https://nostarch.com/hardwarehacking)
4. [The Car Hacker's Handbook by Craig Smith (No Starch, free)](https://nostarch.com/carhacking) - CAN bus, OBD-II, ECU.
5. [Attacking Network Protocols by James Forshaw (No Starch)](https://nostarch.com/networkprotocols) - Applicable to IoT protocols too.
6. [Embedded Systems Security by David Kleidermacher, Mike Kleidermacher](https://www.amazon.com/Embedded-Systems-Security-Hardware-Software/dp/0123868866)
7. [Practical Hardware Pentesting by Jean-Georges Valle (Packt)](https://www.packtpub.com/product/practical-hardware-pentesting/9781789619133)
8. [Bluetooth Low Energy Security - Academic survey papers](https://www.bluetooth.com/bluetooth-resources/)

## Videos
1. [Flashback Team (Pedro Ribeiro) talks](https://www.youtube.com/results?search_query=pedro+ribeiro+flashback)
2. [DEF CON IoT Village](https://www.iotvillage.org/) and [Car Hacking Village](https://www.carhackingvillage.com/)
3. [Hardwear.io talks](https://www.youtube.com/@HardwearIO)
4. [Joe Grand (Kingpin) - hardware hacking talks](https://www.youtube.com/@JoeGrandofficial)
5. [stacksmashing - Flipper Zero, embedded RE](https://www.youtube.com/@stacksmashing)
6. [LiveOverflow - embedded and binary](https://www.youtube.com/@LiveOverflow)
7. [Great Scott Gadgets (Michael Ossmann, HackRF)](https://www.youtube.com/@GreatScottGadgets)
8. [EmbeddedCTF and CTF streamers](https://www.youtube.com/results?search_query=hardware+ctf)

## Free/Paid Courses
### Free
1. [OWASP IoT Security Verification Standard (ISVS) + IoT Top 10](https://owasp.org/www-project-iot-security-verification-standard/)
2. [Azeria Labs ARM Assembly and exploitation (free)](https://azeria-labs.com/writing-arm-assembly-part-1/)
3. [Nicolas Oberli - BLE workshop materials](https://github.com/kmkz/IoT-SecurityTools)
4. [TryHackMe - IoT / Hardware rooms](https://tryhackme.com/)
5. [Embedded Security CTF by Microcorruption (free)](https://microcorruption.com/login) - Highly recommended; MSP430 firmware exploitation.
6. [MITRE EMB3D threat model (free)](https://emb3d.mitre.org/) - Embedded-device threat model released 2024.
7. [OnlySecurity IoT and Hardware Hacker learning path](https://onlysecurity.com/learning-paths/iot-hardware-hacker/) - Eight free courses on Electronic Cats CatSniffer and Minino, Bus Pirate and fault injection. Free account required.

### Paid
8. [SANS SEC556: IoT Penetration Testing (GIAC GICSP also adjacent)](https://www.sans.org/cyber-security-courses/iot-penetration-testing/)
9. [Attify - Offensive IoT Exploitation](https://www.attify.com/offensive-iot-exploitation)
10. [8kSec - Embedded / IoT training](https://academy.8ksec.io/)
11. [Hardwear.io trainings](https://hardwear.io/)
12. [Nccgroup / ToolsWatch trainings](https://research.nccgroup.com/)
13. [OffSec EXP-301 / EXP-401 (OSED/OSEE)](https://www.offsec.com/) - Useful for native firmware exploitation.

## Free/Paid Labs
1. [Microcorruption CTF](https://microcorruption.com/login) - Essential for embedded exploitation basics.
2. [IoTGoat by OWASP](https://github.com/OWASP/IoTGoat) - Deliberately vulnerable firmware (OpenWrt-based).
3. [Damn Vulnerable Router Firmware (DVRF)](https://github.com/praetorian-inc/DVRF)
4. [emulation via QEMU + firmadyne / FirmAE for router firmware](https://github.com/pr0v3rbs/FirmAE)
5. [HackTheBox Hardware challenges](https://www.hackthebox.com/)
6. [Embedded Security CTF archives (CSAW, HITB)](https://ctftime.org/ctf-wtf/)
7. [Flare-On embedded challenges (occasional)](https://flare-on.com/)
8. [NCC Group - firmware-based challenges](https://research.nccgroup.com/)
9. [Attify Labs - paid hands-on](https://www.attify.com/)

## IoT / Hardware Tools
### Firmware analysis
1. [binwalk](https://github.com/ReFirmLabs/binwalk) - Firmware extraction.
2. [firmware-mod-kit / firmwalker / FACT](https://github.com/fkie-cad/FACT_core) - Firmware analysis / classification.
3. [EMBA](https://github.com/e-m-b-a/emba) - Fully-automated firmware security analyzer.
4. [Ghidra](https://ghidra-sre.org/) / [IDA Pro](https://hex-rays.com/) / [Binary Ninja](https://binary.ninja/)
5. [radare2 / Cutter](https://rada.re/)
6. [LIEF](https://lief.re/) - Parse ELF/PE/Mach-O.
7. [Qiling](https://qiling.io/) / [Unicorn](https://www.unicorn-engine.org/) - Emulate embedded binaries.
8. [Trufflehog / gitleaks](https://github.com/trufflesecurity/trufflehog) - Find leaked secrets in firmware.
9. [FirmAE](https://github.com/pr0v3rbs/FirmAE) / [Firmadyne](https://github.com/firmadyne/firmadyne) - Firmware emulation.

### Hardware interfaces
10. [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate) - Multi-protocol debug.
11. [JTAGulator by Joe Grand](https://www.grandideastudio.com/jtagulator/)
12. [Saleae Logic analyzers](https://www.saleae.com/)
13. [Hantek / Rigol / Siglent oscilloscopes](https://www.siglenteu.com/)
14. [ChipWhisperer by NewAE](https://www.newae.com/chipwhisperer) - Side-channel analysis.
15. [Attify Badge / Tigard / BlackBox](https://www.attify-store.com/)
16. [FT232H / CP2102 USB-to-serial adapters](https://www.adafruit.com/)
17. [SEGGER J-Link, ST-LINK, Black Magic Probe](https://www.segger.com/products/debug-probes/j-link/)

### Radio / SDR / BLE / Zigbee
18. [HackRF One](https://greatscottgadgets.com/hackrf/)
19. [RTL-SDR (cheap entry)](https://www.rtl-sdr.com/)
20. [Ubertooth One (classic BLE)](https://greatscottgadgets.com/ubertoothone/)
21. [BladeRF / LimeSDR](https://www.nuand.com/)
22. [GNU Radio](https://www.gnuradio.org/)
23. [GQRX / SDR#](https://gqrx.dk/)
24. [Universal Radio Hacker (URH)](https://github.com/jopohl/urh)
25. [Bettercap BLE modules](https://www.bettercap.org/)
26. [Bluefruit LE / nRF Connect / Ellisys Bluetooth Explorer](https://www.nordicsemi.com/Products/Development-tools/nRF-Connect-for-mobile)
27. [KillerBee (Zigbee)](https://github.com/riverloopsec/killerbee)
28. [Z-Stick + Z-Wave sniffing tools](https://github.com/jhdscript/zwave-js-tools)
29. [Flipper Zero](https://flipperzero.one/) - Multi-protocol hacking handheld.
30. [Proxmark3 (RFID/NFC)](https://proxmark.com/)
31. [Chameleon Mini / Tiny](https://shop.kasper.it/) - NFC emulation.

### Network / IoT-specific
32. [MQTT explorer / MQTT.fx](https://mqtt-explorer.com/)
33. [CoAP client / libcoap](https://libcoap.net/)
34. [Modbus-CLI / Modscan (also relevant to ICS)](https://github.com/tallakt/modbus-cli)
35. [Attify IoT Exploitation Framework (AIEF)](https://github.com/attify)

## Certifications
1. [GIAC GICSP (ICS/IoT overlap)](https://www.giac.org/certifications/global-industrial-cyber-security-professional-gicsp/)
2. [Offensive IoT Pentester (OIP) by Attify](https://www.attify.com/offensive-iot-exploitation)
3. [SANS SEC556 / GIAC Certified IoT Security (GRID/IoT)](https://www.sans.org/cyber-security-courses/iot-penetration-testing/)
4. [OSEE by OffSec (advanced native exploitation)](https://www.offsec.com/courses/exp-401/)
5. [CREST Certified IoT Specialist (in select regions)](https://www.crest-approved.org/)

## Blogs/Articles
1. [OWASP IoT Top 10](https://owasp.org/www-project-internet-of-things/)
2. [OWASP Firmware Security Testing Methodology (FSTM)](https://github.com/scriptingxss/owasp-fstm)
3. [OWASP IoT Security Verification Standard (ISVS)](https://owasp.org/www-project-iot-security-verification-standard/)
4. [MITRE EMB3D threat model for embedded devices](https://emb3d.mitre.org/)
5. [IoT Village blog](https://www.iotvillage.org/resources.html)
6. [Attify IoT blog](https://www.attify.com/blog)
7. [NCC Group research - hardware / embedded](https://research.nccgroup.com/category/hardware-research/)
8. [Pen Test Partners blog - IoT & Automotive](https://www.pentestpartners.com/security-blog/)
9. [Quarkslab blog](https://blog.quarkslab.com/)
10. [IoT Inspector / Andrew Tierney blog](https://www.pentestpartners.com/)
11. [Azeria Labs ARM tutorials](https://azeria-labs.com/)
12. [Hardware Hacking resources by Joe Grand](https://www.grandideastudio.com/)
13. [Awesome Embedded and IoT Security GitHub](https://github.com/fkie-cad/awesome-embedded-and-iot-security)
14. [Awesome Hardware Hacking GitHub](https://github.com/abhijithvijayan/awesome-hardware-hacking)
15. [ENISA IoT / Good Practices for Security of IoT](https://www.enisa.europa.eu/publications)
16. [NISTIR 8259 / 8228 - IoT device cybersecurity guidance](https://csrc.nist.gov/publications)
