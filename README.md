# Advanced Hacking Prevention

This repository contains lab exercises focused on simulating and preventing network attacks using **pfSense** and **Snort**. These labs were conducted as part of an advanced hacking prevention course, covering the setup, configuration, and application of firewall rules and intrusion detection/prevention systems (IDS/IPS).

## Labs

### pfSense Labs

1. Basic Setup:
   [pfsense basic setup.pdf](https://github.com/user-attachments/files/17353249/pfsense.basic.setup.pdf)

    **Description**: Initial setup and installation of pfSense, a free, open-source firewall and router software. This lab covers the installation process, configuration of basic settings, and preparation for network management.

2. Interface Configuration:
   [pfsense interface config.pdf](https://github.com/user-attachments/files/17353259/pfsense.interface.config.pdf)

    **Description**: Configuring the network interfaces within pfSense. This lab includes steps for assigning WAN, LAN, and optional interfaces, ensuring connectivity and network segmentation.

3. DHCP Server Configuration:
   [pfsense dhcp server config.pdf](https://github.com/user-attachments/files/17353258/pfsense.dhcp.server.config.pdf)

    **Description**: Setting up the DHCP server on pfSense to automatically assign IP addresses to clients within the network. Covers configuration of DHCP pools, leases, and IP reservations.

4. NAT and Firewall Rules:
   [pfsense nat and firewall.pdf](https://github.com/user-attachments/files/17353260/pfsense.nat.and.firewall.pdf)

    **Description**: Configuration of Network Address Translation (NAT) and creation of firewall rules to manage traffic flow. This lab explains how to allow and block traffic based on source, destination, and protocol.

5. VPN Configuration:
    [pfsense vpn config.pdf](https://github.com/user-attachments/files/17353262/pfsense.vpn.config.pdf)

    **Description**: Setting up a Virtual Private Network (VPN) using pfSense. This lab demonstrates how to configure OpenVPN for secure remote access to the internal network.

6. VLANs and Multi-LAN Setup:
    [pfsense vlan and multi-lan setup.pdf](https://github.com/user-attachments/files/17353261/pfsense.vlan.and.multi-lan.setup.pdf)
  
   **Description**: Configuring VLANs (Virtual Local Area Networks) and multiple LAN segments. This lab shows how to create isolated network segments and apply security rules between them.

### Snort Labs

1. Basic Snort Installation and Configuration:
    [Snort Basic Snort Installation and Configuration.docx.pdf](https://github.com/user-attachments/files/17353263/Snort.Basic.Snort.Installation.and.Configuration.docx.pdf)

   **Description**: Installation and initial configuration of Snort, an open-source IDS/IPS. The lab covers how to install Snort on pfSense and set up the necessary configurations to begin monitoring network traffic.

2. Rule Writing and Alerts:
   [snort-rule writing and alerts.docx.pdf](https://github.com/user-attachments/files/17353267/snort-rule.writing.and.alerts.docx.pdf) 

   **Description**: Creating custom Snort rules to detect malicious traffic. This lab focuses on writing rules to generate alerts based on specific patterns in network packets.

3. Integrating Snort with PulledPork:
    [Snort Integrating Snort with PulledPork.docx.pdf](https://github.com/user-attachments/files/17353265/Snort.Integrating.Snort.with.PulledPork.docx.pdf)

   **Description**: Setting up PulledPork, a tool that helps manage Snort rule updates. This lab explains how to configure PulledPork to automatically update and manage Snort rules efficiently.

4. Traffic Analysis and Snort Preprocessors:
    [Snort Traffic Analysis and Snort Preprocessors.docx.pdf](https://github.com/user-attachments/files/17353266/Snort.Traffic.Analysis.and.Snort.Preprocessors.docx.pdf)
   
   **Description**: Understanding how Snort preprocessors work to normalize and analyze traffic. This lab explores various Snort preprocessors that help detect complex attacks by inspecting the network traffic in real-time.

5. Snort IDS to IPS Mode:
   [Snort IDS and IPS Mode.docx.pdf](https://github.com/user-attachments/files/17353264/Snort.IDS.and.IPS.Mode.docx.pdf)
   
   **Description**: Transitioning Snort from an Intrusion Detection System (IDS) to an Intrusion Prevention System (IPS). This lab demonstrates how to block malicious traffic in real-time rather than just alerting on it.

---

Explore more cybersecurity tools and techniques through the labs listed above.
