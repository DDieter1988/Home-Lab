## June 21–22, 2025

### Windows Server 2022 + Active Directory
- Installed Server 2022 Standard Evaluation in VirtualBox
- Promoted to Domain Controller with domain `example.local`
- Set static IPs for consistency
- Installed RSAT on Win10 Enterprise VM
- Created and linked GPOs
- Mapped network drives via GPO

### WireGuard VPN
- Installed WireGuard on host VM
- Generated and exchanged key pairs
- Configured port forwarding on SAC2V1K (UDP 51820)
- Connected successfully from Android phone via LTE
- Tested internal access: ping, SMB, RDP (via RustDesk)

### RustDesk Setup
- Installed RustDesk for RDP-like functionality (Win10 Home limitation)
- Remoted into desktop via VPN from phone

### Notes
- Skipping VLAN setup for now (unmanaged switch); will revisit with pfSense in VirtualBox
- Gained experience troubleshooting DNS, network adapter conflicts, RSAT installs
