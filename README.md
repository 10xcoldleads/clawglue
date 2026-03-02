# Launch My OpenClaw

**Secure Remote Desktop Environment — powered by OpenClaw**

https://Launchmyopenclaw.com

*In collaboration with Jeff & Brandan*
*Originally forked from SecureClaw by Brandon Belew — modified with full attribution*

---

## What is Launch My OpenClaw?

Launch My OpenClaw is a one-command installer that transforms a fresh Ubuntu VPS into a fully secured remote desktop environment with:

- Remote Desktop (RDP) access via XRDP
- Tailscale VPN for secure, encrypted remote connectivity
- OpenClaw AI assistant running as a background service
- Google Chrome browser
- Firewall hardening (UFW) locked down to Tailscale subnet only
- Desktop control panel widget for service monitoring

## Join the Community

We're building a group of power users who deploy and manage OpenClaw environments. Come join us, share your setups, and learn from others:

**https://Launchmyopenclaw.com**

## Setup

**main (stable)**
```bash
wget -qO /tmp/lmo-install.sh https://raw.githubusercontent.com/10xcoldleads/clawglue/main/install.sh && sudo bash /tmp/lmo-install.sh
```

**dev (latest)**
```bash
wget -qO /tmp/lmo-install.sh https://raw.githubusercontent.com/10xcoldleads/clawglue/dev/install.sh && sudo bash /tmp/lmo-install.sh dev
```

## Credits

This project is a fork of [SecureClaw](https://github.com/brandonbelew/secureclaw) by **Brandon Belew** (Craw-Kan Telephone). We are grateful for the original work by Jeff & Brandan that made this possible. This project has been modified and rebranded for the Launch My OpenClaw community while maintaining ethical attribution to the original authors.

## License

MIT License — see [LICENSE](LICENSE) for details.
