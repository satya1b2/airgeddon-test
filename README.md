# airgeddon-test

Test environment for installing, configuring, and experimenting with the **airgeddon** wireless security auditing toolkit on Kali Linux and other penetration-testing distributions.

> airgeddon is a multi-use bash script for Linux systems to audit wireless networks, supporting features like Evil Twin attacks, handshake/PMKID capture, and WPA/WPA2/WPA3 cracking workflows.
## Purpose

- Practice installing and updating airgeddon from source.
- Test wireless attack workflows in a controlled lab setup.
- Experiment with different wireless adapters, drivers, and configurations.
- Keep notes, scripts, and configs specific to this setup.

## Requirements

- A Linux-based OS (e.g., Kali, Parrot, or Ubuntu) with a compatible wireless adapter.  
- Common wireless tools such as `aircrack-ng`, `hashcat`, `macchanger`, etc. (many are auto-detected by airgeddon).

## Getting Started

1. Clone this test repo:


git clone [https://github.com/satya1b2/airgeddon-test.git](https://github.com/satya1b2/airgeddon-test.git)
cd airgeddon-test
text

2. Clone the upstream airgeddon project (or ensure it is installed on your system):


git clone [https://github.com/v1s1t0r1sh3r3/airgeddon.git](https://github.com/v1s1t0r1sh3r3/airgeddon.git)
cd airgeddon
sudo bash airgeddon.sh
text

3. Use this repo to store:
- Notes on commands and attack flows.
- Custom scripts or helpers around airgeddon.
- Configurations, logs (sanitized), and screenshots.

## Disclaimer

This project is for educational and authorized security testing only. Do not use airgeddon or any related tools against networks you do not own or have explicit permission to test.
