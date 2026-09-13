# Rami Kilany

**IT Infrastructure Consultant — Lebanon 🇱🇧**

I build infrastructure around two ideas: **own your data** and **software-defined infrastructure**.

18+ years in IT, most of it in hospitals and healthcare, where downtime is not an inconvenience and
"we'll fix it next quarter" is not an answer. I work as an independent consultant: concept and
architecture work for organizations that want a design stress-tested before they commit budget to
it, and full build-and-operate for the ones without an in-house team.

Most of what you'll find in these repos is tooling, runbooks and documentation that came out of real
work.

---

## The two ideas I build around

### 🔐 Own your data

Every convenience you rent is a dependency you don't control — pricing, availability, retention,
and who gets to read it. Almost every hosted service has a self-hosted equivalent that is good
enough to run a business or a household on, and the gap keeps closing.

| Instead of renting | Own it |
| --- | --- |
| Your code on someone else's forge | **Forgejo** |
| Your files and calendars in a hosted drive | **Nextcloud** |
| Your home automation in a vendor cloud | **Home Assistant**, local-first |
| Your media in a streaming subscription | **Jellyfin** |
| Your backups in someone else's region | **ZFS** snapshots, replication, and offsite copies you verify |

Self-hosting only counts if it's survivable. That means snapshots, tested restores, monitoring, and
a documented way to rebuild it — otherwise you haven't taken ownership of your data, you've just
taken responsibility for losing it.

### 🧱 Software-defined infrastructure — no vendor lock-in

The reason that matters is independence. When the platform is open and the configuration is written
down, the hardware underneath becomes a commodity decision instead of a commitment:

- **Buy on merit, not on lock-in.** Any vendor's server, any disk controller, any switch — chosen on
  price, warranty and availability rather than on what your existing licences will tolerate.
- **Hardware failure becomes an inconvenience, not an incident.** A node dies, you restore onto
  different hardware from a different vendor, and the workload doesn't know the difference.
- **No licence holding your data hostage.** Open formats, open hypervisors, open storage. Your
  ability to move is never something you have to renew.
- **Own your hardware.** On-premise, colocated, or rented by the month — the point is that the
  decision stays reversible, and moving between them is a migration you plan rather than a
  negotiation you lose.

---

## What I can be hired for

| Area | What that looks like in practice |
| --- | --- |
| **Virtualization & migration** | Proxmox VE / Proxmox Backup Server design on bare metal or hosted. VMware ESXi → Proxmox migrations, including the Windows Server / SQL Server side: disk bus and CPU model correctness, ballooning, storage layout, backup and restore verification. |
| **Self-hosting & data ownership** | Designing and building the self-hosted stack that replaces rented services — identity, files, code, automation, media — with the storage, backup and update strategy that makes it sustainable. |
| **Storage & data protection** | TrueNAS SCALE and ZFS design, dataset and snapshot policy, replication and offsite sync, ransomware detection and recovery planning. Restores tested, not assumed. |
| **Observability** | Prometheus and Grafana for metrics, Loki for logs, Zabbix for classic infrastructure monitoring, Uptime Kuma for availability, and alerting with priorities that mean something — so alerts get read instead of muted. |
| **Security & blue teaming** | Defence from the host up: server hardening against a real baseline, service and network segmentation, and web application hardening against the OWASP Top 10 , access control and misconfiguration classes that actually get exploited. **Wazuh** for detection, log correlation and file integrity monitoring. And offensive-side validation of your own estate — scanned and tested the way an attacker would, before someone else does it for you. |
| **Networking & remote access** | OPNsense, VLANs and segmentation, overlay networks with NetBird / WireGuard, nginx and Traefik reverse proxies, automated TLS. |
| **Containers** | Docker Engine on Linux — image hygiene, Compose, registries, rootless and socket hardening, resource limits. The operational side, not the demo. |
| **Healthcare IT** | Hospital Information System architecture — HL7 and FHIR interfaces, DICOM and PACS (Orthanc / OHIF), integration middleware (Mirth Connect), and the plumbing between clinical systems that nobody wants to own. |
| **Documentation & training** | Living runbooks as a deliverable, plus technical training built and delivered for internal teams. |

---

## Tech I work with

**Virtualization & storage**

![Proxmox](https://img.shields.io/badge/Proxmox%20VE-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Proxmox Backup Server](https://img.shields.io/badge/Proxmox%20Backup-E57000?style=flat-square&logo=proxmox&logoColor=white)
![TrueNAS](https://img.shields.io/badge/TrueNAS%20SCALE-0095D5?style=flat-square&logo=truenas&logoColor=white)
![ZFS](https://img.shields.io/badge/ZFS-0095D5?style=flat-square)
![VMware](https://img.shields.io/badge/VMware%20ESXi-607078?style=flat-square&logo=vmware&logoColor=white)
![Linode / Akamai](https://img.shields.io/badge/Linode%20%2F%20Akamai-0099CC?style=flat-square&logo=akamai&logoColor=white)

**Operating systems**

![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=flat-square&logo=fedora&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-1A1A1A?style=flat-square&logo=linux&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D6?style=flat-square)

**Networking & remote access**

![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![NetBird](https://img.shields.io/badge/NetBird-1B1B1B?style=flat-square)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white)

**Containers & automation**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Forgejo](https://img.shields.io/badge/Forgejo-FB923C?style=flat-square&logo=forgejo&logoColor=white)

**Observability & security**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F46800?style=flat-square)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square)
![Wazuh](https://img.shields.io/badge/Wazuh-005C8A?style=flat-square)
![Uptime Kuma](https://img.shields.io/badge/Uptime%20Kuma-5CDD8B?style=flat-square&logo=uptimekuma&logoColor=white)
![ntfy](https://img.shields.io/badge/ntfy-317F6F?style=flat-square)

**Self-hosted platform**

![Nextcloud](https://img.shields.io/badge/Nextcloud-0082C9?style=flat-square&logo=nextcloud&logoColor=white)
![Home Assistant](https://img.shields.io/badge/Home%20Assistant-41BDF5?style=flat-square&logo=homeassistant&logoColor=white)
![Jellyfin](https://img.shields.io/badge/Jellyfin-00A4DC?style=flat-square&logo=jellyfin&logoColor=white)

**Healthcare interoperability**

![HL7](https://img.shields.io/badge/HL7-2E4A62?style=flat-square)
![FHIR](https://img.shields.io/badge/FHIR-B02A37?style=flat-square)
![DICOM](https://img.shields.io/badge/DICOM%20%2F%20PACS-2E4A62?style=flat-square)
![Mirth Connect](https://img.shields.io/badge/Mirth%20Connect-4B7A9E?style=flat-square)

---

## Contact

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Message%20me-25D366?style=flat-square&logo=whatsapp&logoColor=white)](https://wa.me/9613851770)
[![Email](https://img.shields.io/badge/Email-ramikilany%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ramikilany@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rami%20Kilany-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rami-kilany-b7122091/)
