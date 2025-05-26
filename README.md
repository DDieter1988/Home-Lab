# Daniel Dieter's Home Lab Portfolio

Welcome to my home lab! I'm building this environment to sharpen my skills in networking, systems administration, virtualization, and IT infrastructure. This portfolio documents my journey—from physical hardware to software services—and serves as a hands-on foundation for launching my career in IT.

---

## Goals

- Develop real-world experience with IT tools and infrastructure
- Learn to design and troubleshoot small-scale networks
- Practice virtualization, firewalls, and network services
- Build a portfolio to showcase to potential employers

---

## Current Network Overview

**Network Topology (May 2025):**

           [Internet]
               |
               |
         [ISP Modem]
               |
               |
      [ISP Router/Wi-Fi] (in smart panel)
               |
     +---------+-----------+
     |                     |
 [Cat6 Wall Jack]      [Other unused ports]
     |
     |  (Existing pre-run Ethernet)
     |
 [Bedroom Wall Jack]
     |
     |  
+-------------+
| Linksys |
| LGS108P V2 | (Unmanaged PoE Switch)
+------+------+---------------------+
| |
[My PC] [Xbox Console]


---

## Hardware Inventory

| Device        | Specs                          | Role                                 |
|---------------|----------------------------------|--------------------------------------|
| Main PC       | Ryzen 3 2200G / 16GB RAM / 1TB SSD | Daily driver, future VM host         |
| Switch        | Linksys LGS108P V2 (8-port PoE) | LAN switch for devices + future APs  |

---

## Services Running

Currently no dedicated services or servers running—this portfolio will evolve as I add hardware and tools.

---

## Future Plans

In progress: building a flexible, low-cost lab focused on realistic IT skills. Here's what I plan to implement as time and budget allow:

- 🔧 **Replace ISP router** with a custom pfSense box (possibly using SFF hardware)
- 🖧 **Add attic-mounted PoE Wi-Fi access points** for whole-home coverage
- 📦 **Install Proxmox VE** on repurposed or refurbished hardware
- 🐳 **Set up Docker containers** (Pi-hole, Portainer, HomeLab Dashboard)
- 📋 **Document lab build process**: photos, diagrams, configs
- 📡 **Experiment with VLANs and network segmentation**
- 🔐 **Implement firewall rules and monitoring tools** (Syslog, ntopng, etc.)
- 🌐 **Host portfolio on GitHub Pages or local web server**
- 🧪 **Learn and apply basic scripting** (Bash, PowerShell, Python)

---

## About Me

I'm Daniel, a self-taught tech enthusiast preparing for a career in IT with a focus on networking and systems. I'm actively learning through hands-on experience, online courses, and certifications (like CompTIA A+). I believe in building things that teach—and this lab is my foundation.

Let’s connect: www.linkedin.com/in/daniel-dieter-IT


