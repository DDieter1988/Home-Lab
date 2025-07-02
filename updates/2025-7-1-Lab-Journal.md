# 🔌 Network Update — D-Link DGS-1008V2 Switch Setup (July 1, 2025)

Today I installed and configured the **D-Link DGS-1008V2**, a smart managed switch that supports VLANs, QoS, and a web-based GUI. This is the first step toward segmenting and managing my growing home lab network.

---

## 🛠️ What I Did

- **Physically installed** the switch and connected it to my network
- Discovered that the switch was on a **different subnet** than my LAN
- Manually **adjusted my PC’s IP address** and subnet prefix to match
- Successfully **logged into the web GUI**
- Reconfigured the switch’s IP to **match my primary subnet**
- Verified connectivity and access from the rest of the network

---

## Lessons Learned

- Some smart switches ship with IPs in default subnets (e.g. `10.90.90.90`) that may not match your LAN
- Adjusting subnet and prefix manually is essential for initial access
- Always move devices to your main subnet as soon as possible for easier management

---

## Next Steps

- Begin testing **802.1Q VLAN tagging**
- Assign port-based VLANs for lab devices and future APs
- Experiment with **QoS rules** for media traffic
- Document configuration for reproducibility

---

## Device Info

| Device                  | Value                        |
|-------------------------|------------------------------|
| Model                   | D-Link DGS-1008V2            |
| IP Address (New)        | `192.168.X.X` (LAN range)    |
| VLAN Support            | Yes (802.1Q)                 |
| QoS                     | Yes                          |
| Management Access       | Web GUI (no cloud needed)    |

