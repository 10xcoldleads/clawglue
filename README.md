# Launch My OpenClaw

**Secure Remote Desktop Environment — powered by OpenClaw**

https://Launchmyopenclaw.com

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

## License

MIT License — see [LICENSE](LICENSE) for details.
