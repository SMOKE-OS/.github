<div align="center">

# 🌫️ SMOKE OS

**Minimal by design. Powerful by nature.**

*A minimal, high-performance Arch Linux distribution powered by Hyprland.*

[![Arch Linux](https://img.shields.io/badge/Base-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)](https://archlinux.org/)
[![Hyprland](https://img.shields.io/badge/Compositor-Hyprland-00AAFF?style=for-the-badge&logo=wayland&logoColor=white)](https://hyprland.org/)
[![Wayland](https://img.shields.io/badge/Display-Wayland-FF6600?style=for-the-badge&logo=wayland&logoColor=white)](https://wayland.freedesktop.org/)
[![Status](https://img.shields.io/badge/Status-Early%20Alpha-yellow?style=for-the-badge)](https://github.com/SMOKE-OS)
[![License](https://img.shields.io/badge/License-GPLv3%20%2F%20MIT-blue?style=for-the-badge)](https://github.com/SMOKE-OS)

<p align="center">
  <b>Less clutter. More control. Pure Linux.</b>
</p>

---

</div>

## 📖 About SMOKE OS

**SMOKE OS** is an independent Linux distribution crafted on top of **Arch Linux** and tailored around the **Hyprland** dynamic tiling Wayland compositor.

Our mission is to deliver a sleek, coherent, and ultra-responsive desktop experience out of the box—eliminating bloat while preserving user freedom, granular extensibility, and peak performance.

> *"Great software doesn't need unnecessary complexity."*

---

## ⚡ Core Philosophy

<table>
  <tr>
    <td width="50%">
      <h3>🎯 Minimalism</h3>
      <p>Every default package and service must justify its presence. No bloat, no redundant background daemons.</p>
    </td>
    <td width="50%">
      <h3>🚀 Performance</h3>
      <p>Sub-second boot times, minimal memory footprint, and low-latency Wayland responsiveness.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎨 Visual Cohesion</h3>
      <p>Meticulously tuned color palettes, unified font rendering, fluid animations, and polished Waybar integration.</p>
    </td>
    <td width="50%">
      <h3>🔓 Freedom & Transparency</h3>
      <p>100% open source, completely reproducible builds, and zero telemetry.</p>
    </td>
  </tr>
</table>

---

## 🛠️ Technology Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Base System** | [Arch Linux](https://archlinux.org/) | Rolling-release upstream base & package repositories |
| **Compositor** | [Hyprland](https://hyprland.org/) | Modern, fluid dynamic tiling Wayland compositor |
| **Status Bar** | [Waybar](https://github.com/Alexays/Waybar) | Customizable status bar with native Wayland protocols |
| **Package Management** | `pacman` | Fast native package manager with AUR support |
| **Init & Service Manager** | `systemd` | System and service management |
| **ISO Builder** | `archiso` | Reproducible live ISO generation toolkit |
| **Bootloader** | `systemd-boot` | Fast, modern UEFI bootloader |
| **Boot Splash** | `plymouth` | Smooth graphical boot transitions |

> [!NOTE]
> Planned components may evolve as development progresses. Check individual repositories for active specifications.

---

## 🚧 Project Roadmap & Status

> [!WARNING]
> **SMOKE OS is currently under active, early development.** Builds are experimental. Always test early releases in a virtual machine (QEMU/KVM, Virt-Manager) before considering physical hardware.

- [ ] **Reproducible ISO**: Establish automated `archiso` build pipeline.
- [ ] **Hyprland Experience**: Curate sane defaults, keybindings, and dynamic window rules.
- [ ] **Aesthetic Identity**: Unified themes, custom wallpapers, and Plymouth boot splash.
- [ ] **Installer & Setup**: Streamlined guided installer and post-install configuration scripts.
- [ ] **Automated CI/CD**: Nightly build verification and artifact releases.

---

## 🤝 Contributing

We welcome community feedback, feature discussions, and contributions!

- 🐛 **Bug Reports**: Open an issue with full system specifications and reproducible steps.
- 💡 **Feature Requests**: Propose ideas detailing practical use cases and design integration.
- 🛠️ **Code Contributions**: Submit PRs with tested, documented changes adhering to our minimalism principle.
- 📜 **Attribution**: Respect the licensing and copyright of all upstream projects.

---

## ⚖️ Legal & Licensing

SMOKE OS is an independent community project and is **not officially affiliated with, endorsed by, or sponsored by** Arch Linux or Hyprland.

- Upstream components retain their respective copyrights, licenses, and trademarks.
- Original SMOKE OS scripts, configurations, and brand artwork are distributed under open-source licenses as documented in their corresponding repositories.

---

<div align="center">

**SMOKE OS**  
*Find clarity in the chaos.*

</div>
