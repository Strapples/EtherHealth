EtherHealth - Open Source Networked Medical Biometric Monitoring

Description

EtherHealth is an open-source library of hardware and software designed to bring medical biometric data online using Ethernet and IP packets to transmit real-time medical telemetry. By leveraging standardized networking protocols, this system enables seamless monitoring and data acquisition from anywhere on a local network or the internet.

Key Features:

Uses TCP/IP for data transmission, ensuring compatibility with existing network infrastructure.

PoE (Power over Ethernet) ready, reducing the need for additional power cables.

Scalable architecture, allowing multiple sensors to connect to a single monitoring hub.

Telnet-accessible raw data, making it easy to integrate with research tools, dashboards, or simple CLI interfaces.

Open-source and hospital-friendly, requiring only a link back to this GitHub repository for usage in medical environments.

Bill of Materials (BOM)

Below are three different build levels to match different use cases:

1️⃣ Minimum Viable Build (EEG + SpO2, No ECG)

A streamlined setup for basic neurophysiological monitoring and blood oxygen tracking.

Component

Purpose

Link

Price (USD)

EEG Headband

EEG Monitoring

Amazon

~$65.25

MAX30102 Sensor

SpO2 & Heart Rate

Amazon

~$12.70

Raspberry Pi 5 (8GB RAM)

Processing Unit

Amazon

~$89.99

SanDisk 64GB MicroSD

Storage for OS & Data

Amazon

~$10.91

USB-C Power Supply (5V/5A)

Powering RPi

Amazon

~$16.99

0.96-inch OLED I2C Display (5-Pack)

Small Data Display

Amazon

~$14.88

RJ45 Network Cables

Networking

Various

~$10

RJ45 Splitters & Adapters

Multiple Sensor Connectivity

Various

~$10

➡️ Total Cost: ~$220 - $250

2️⃣ Full Build (ECG + BIS + SpO2)

A complete biometric suite with 5-lead ECG monitoring, brain activity monitoring (BIS), and SpO2 tracking.

Component

Purpose

Link

Price (USD)

EEG Headband

EEG Monitoring

Amazon

~$65.25

MAX30102 Sensor

SpO2 & Heart Rate

Amazon

~$12.70

ADS1292R Board

ECG 5-Lead Data Capture

Amazon

~$49.92

5-Lead ECG Snap Cable

Standard ECG Electrode Cable

Amazon

~$42.99

Raspberry Pi 5 (8GB RAM)

Processing Unit

Amazon

~$89.99

SanDisk 64GB MicroSD

Storage for OS & Data

Amazon

~$10.91

USB-C Power Supply (5V/5A)

Powering RPi

Amazon

~$16.99

0.96-inch OLED I2C Display (5-Pack)

Small Data Display

Amazon

~$14.88

RJ45 Network Cables

Networking

Various

~$10

RJ45 Splitters & Adapters

Multiple Sensor Connectivity

Various

~$10

➡️ Total Cost: ~$350 - $400

3️⃣ Extreme Build (Full Biometric Suite + Temperature Monitoring + Advanced Networking)

The ultimate networked biometric monitoring system, including temperature sensing and extended logging capabilities.

Component

Purpose

Link

Price (USD)

EEG Headband

EEG Monitoring

Amazon

~$65.25

MAX30102 Sensor

SpO2 & Heart Rate

Amazon

~$12.70

ADS1292R Board

ECG 5-Lead Data Capture

Amazon

~$49.92

5-Lead ECG Snap Cable

Standard ECG Electrode Cable

Amazon

~$42.99

DS18B20 Temperature Probe

Body Temperature Monitoring

Amazon

~$8.89

Raspberry Pi 5 (8GB RAM)

Processing Unit

Amazon

~$89.99

SanDisk 64GB MicroSD

Storage for OS & Data

Amazon

~$10.91

USB-C Power Supply (5V/5A)

Powering RPi

Amazon

~$16.99

0.96-inch OLED I2C Display (5-Pack)

Small Data Display

Amazon

~$14.88

RJ45 Network Cables

Networking

Various

~$10

RJ45 Splitters & Adapters

Multiple Sensor Connectivity

Various

~$10

Custom Enclosure & Mounting Hardware

Protection & Stability

Various

~$20

➡️ Total Cost: ~$450 - $500

Software & Networking

Communication Protocol: TCP/IP

All sensor data is streamed over standard Ethernet using a low-latency TCP/IP socket.

Telnet / Serial Interface: Raw data can be accessed via Telnet for easy debugging and testing.

PoE-Enabled: Future versions will allow sensors to be powered entirely through Ethernet.

Future Additions

NIBP (Non-Invasive Blood Pressure) Support

Integration with existing EHR/FEHR systems

Mobile App for Remote Viewing

AI-Driven Diagnostics & Alerts

This is just the beginning. Let’s revolutionize medical biometrics together. 🚀

🔗 Contribute & Fork: http://github.com/strapples/etherhealth

