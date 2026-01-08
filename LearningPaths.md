# Homelab Learning Paths

Not every homelab has the same goal. These learning paths are designed to help guide your homelab projects based on what you want to learn or build.

Each path is progressive. Start small, master the basics, and add complexity only when it serves a purpose.

---

## Beginner Path – Foundations

This path is for anyone starting their first homelab.

### Goals
- Learn basic Linux administration
- Understand virtualization concepts
- Run a small number of useful services
- Keep costs and power usage low

### Recommended Setup
- Single mini PC or small desktop
- Proxmox VE or a Linux server OS
- SSD-based storage

### Skills to Learn
- SSH access and terminal usage
- File permissions and ownership
- Basic networking (IP, DNS, ports)
- Updating and maintaining systems

### Suggested Projects
- Install a Linux VM
- Deploy Pi-hole
- Run a basic container or LXC
- Configure scheduled backups

---

## Intermediate Path – Virtualization & Networking

This path builds on the fundamentals and introduces more complex infrastructure concepts.

### Goals
- Run multiple services reliably
- Learn networking and segmentation
- Improve monitoring and backups
- Introduce containers at scale

### Recommended Setup
- More RAM (32GB or more)
- NVMe storage
- Managed network switch (optional)

### Skills to Learn
- Virtual machine vs container use cases
- VLAN configuration
- Firewall rules and NAT
- Resource allocation and tuning

### Suggested Projects
- Deploy a firewall (OPNsense or OpenWRT)
- Segment services using VLANs
- Run Docker or multiple LXCs
- Set up monitoring dashboards
- Implement centralized backups

---

## Advanced Path – Infrastructure & Security

This path is focused on enterprise-style infrastructure and security practices.

### Goals
- High availability and redundancy
- Security-focused deployments
- Advanced networking
- Real-world infrastructure simulation

### Recommended Setup
- Multiple Proxmox nodes
- Dedicated storage or NAS
- Separate firewall/router hardware or VM

### Skills to Learn
- Clustering and failover
- Advanced firewall rules
- IDS/IPS tuning
- Certificate management
- Automation and infrastructure as code

### Suggested Projects
- Build a Proxmox cluster
- Deploy Proxmox Backup Server
- Implement WireGuard VPN access
- Add IDS/IPS monitoring
- Automate deployments with scripts or Ansible

---

## Specialized Learning Paths

### Media & Home Services
- Plex or Jellyfin
- ARR applications
- GPU passthrough
- Storage optimization

### Networking & Security
- SD-WAN simulation
- VPN gateways
- Zero Trust concepts
- Network monitoring and traffic analysis

### Development & Testing
- CI/CD pipelines
- Self-hosted Git services
- Test environments for applications

---

## Choosing the Right Path

You do not need to complete every path.

Choose the path that aligns with:
- Your career goals
- Your interests
- The services you actually plan to use

Homelabs are most effective when built with intention.
