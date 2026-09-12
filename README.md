# 🖥️ Sysadmin Learning Journey – NordScale IT-Solutions

Willkommen in meinem Lern-Repository! Hier dokumentiere ich meinen Weg zum **Fachinformatiker für Systemintegration** anhand eines selbst aufgebauten Homelab-Projekts.

## 🎯 Projektidee

Ich baue eine fiktive kleine Firma namens **"NordScale IT-Solutions"** komplett virtuell auf – mit allem, was in einer echten IT-Infrastruktur dazugehört:

- Virtualisierung mit Proxmox
- Netzwerksegmentierung (VLANs, Firewall)
- Windows Server & Active Directory
- Linux-Server (Web, File, Datenbanken)
- Security & Monitoring
- Cloud-Anbindung
- Simulierte Support-Tickets aus dem Arbeitsalltag

Ziel ist es, praxisnahe Skills aufzubauen, die im echten Berufsleben als Systemintegrator gebraucht werden – und das Ganze sauber zu dokumentieren wie in einem echten Unternehmen.

## 🖧 Hardware

**Server:**
- CPU: Intel i5-12500 (6 Kerne / 12 Threads)
- RAM: 64 GB
- Storage:
  - 2x NVMe 1 TB SSD (ZFS RAID 1) – für Proxmox OS & VMs/Container
  - 2x 18 TB HDD MG09 (ZFS RAID 1) – für Massenspeicher/Backups/Datengrab
- Netzwerk: 1x 1 GbE + 1x 2,5 GbE
- USV vorhanden (unterbrechungsfreie Stromversorgung)

**Netzwerk-Infrastruktur:**
- Managed Switch: MS308E
- Router: FritzBox mit 2,5 GbE-Ports
- Internetanbindung: 250 Mbit/s

**Virtualisierung:**
- Hypervisor: Proxmox VE

## 📂 Inhaltsverzeichnis

| Ordner | Thema |
|---|---|
| [00 – Projekt-Planung](./00-projekt-planung/) | Roadmap, Netzwerkplan, IP-Konzept |
| [01 – Proxmox Grundlagen](./01-proxmox-grundlagen/) | Virtualisierung, ZFS, Backups |
| [02 – Netzwerk](./02-netzwerk/) | VLANs, Firewall, Routing |
| [03 – Windows Server & AD](./03-windows-server-ad/) | Active Directory, GPOs, DNS/DHCP |
| [04 – Linux Server](./04-linux-server/) | Webserver, Fileserver, Docker |
| [05 – Security](./05-security/) | Hardening, Monitoring, Backups |
| [06 – Cloud](./06-cloud/) | Nextcloud, Hybrid-Szenarien |
| [07 – Tickets](./07-tickets/) | Simulierte Support-Fälle |
| [99 – Troubleshooting](./99-troubleshooting/) | Fehler & Lösungen (Wissens-Wiki) |

## 🚀 Status

🟢 **Projektstart:** September 2026
📌 Aktuelle Phase: Grundlagen & Planung

## 🛠️ Über mich

Ich befinde mich in der Ausbildung/Umschulung zum Fachinformatiker für Systemintegration und dokumentiere hier meinen praktischen Lernweg – von den Grundlagen bis zu komplexeren Enterprise-Szenarien.

---
*Dieses Repository wird laufend erweitert.*
