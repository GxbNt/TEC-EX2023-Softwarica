# WiFi 2.4GHz Attacking Tools

This repository contains a detailed IoT project developed for the TEC-EX2023 event at Softwarica College, focused on performing WiFi attacks and analysis on the 2.4GHz band. It includes three main projects:

- WiFusion
- SerialAdapt-Hunt
- WiFi Rhapsody

---

## WiFusion

**WiFusion** is a versatile wireless attack tool built using ESP32, SH1106 OLED screen, push buttons, and LEDs.

**Capabilities include:**
- Scanning nearby Wi-Fi Access Points (APs) and Wi-Fi Client Stations (STs)
- Executing targeted attacks:
  - **Deauthentication Attack**: Disconnect devices from Wi-Fi networks.
  - **Beacon Flood Attack**: Flood target areas with fake SSID broadcasts.
  - **Probe Request Flood**: Disrupt connected Wi-Fi client devices.

### Features:
- User-friendly interface via OLED display and physical buttons
- Precise packet monitoring for effective attack targeting
- Easy selection of targets (APs/STs)

---

## SerialAdapt-Hunt

**SerialAdapt-Hunt** is an advanced companion tool that extends WiFusion capabilities through a USB-connected serial terminal interface.

**Key Functionalities:**
- Powerful Command-Line Interface (CLI)
- Advanced scanning capabilities, including probe request analysis and MAC address tracking
- Supports aliasing MAC addresses for easier identification of known devices
- Performs Beacon, Deauthentication, and Probe Request attacks
- Ability to save scan results for future reference

### Advantages:
- Optimized performance leveraging ESP32 hardware (CPU, memory, Wi-Fi transceiver)
- Ideal for comprehensive Wi-Fi analysis and targeted attacks

---

## WiFi Rhapsody

**WiFi Rhapsody** is a comprehensive Wi-Fi monitoring device designed to simultaneously capture and store packets across all 14 channels of the 2.4GHz band.

### Core Features:
- Simultaneous real-time packet capturing and logging across 14 channels
- Data stored in standard `.pcap` format for compatibility with analysis tools
- Built using 14 ESP32 modules, each equipped with an OLED screen and storage (SD card)
- Detects and logs deauthentication packets, aiding in network security analysis and education
- Cost-effective alternative to advanced monitoring tools like WiFi Cactus

