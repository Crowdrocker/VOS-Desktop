# VOS Desktop Environment
## Arch Linux Niri/Hyprland Setup

```
██╗   ██╗ ██████╗ ███████╗
██║   ██║██╔═══██╗██╔════╝
██║   ██║██║   ██║███████╗
╚██╗ ██╔╝██║   ██║╚════██║
 ╚████╔╝ ╚██████╔╝███████║
  ╚═══╝   ╚═════╝ ╚══════╝
```

**A hybrid desktop environment combining the theming excellence of Jakoolit with the workflow efficiency of Omarchy**

[![GitHub](https://img.shields.io/badge/GitHub-Crowdrocker-blue?style=flat-square&logo=github)](https://github.com/Crowdrocker)
[![Arch Linux](https://img.shields.io/badge/Arch-Linux-1793D1?style=flat-square&logo=arch-linux)](https://archlinux.org/)
[![Niri](https://img.shields.io/badge/Window%20Manager-Niri-orange?style=flat-square)](https://github.com/YaLTeR/niri)
[![Hyprland](https://img.shields.io/badge/Window%20Manager-Hyprland-blue?style=flat-square)](https://hyprland.org/)

---

## 🎯 Project Vision

VOS Desktop Environment is a carefully crafted Arch Linux setup that merges two exceptional approaches:
- **Jakoolit's aesthetic excellence** - Beautiful, cohesive theming and visual design
- **Omarchy's functional mastery** - Efficient workflows and productivity-focused features

This setup supports both **Niri** and **Hyprland** window managers, giving you the flexibility to choose your preferred tiling experience while maintaining consistent theming and functionality.

## ✨ Key Features

### 🎨 Visual Excellence
- **Noctalia Shell** - Modern, elegant shell interface replacing traditional status bars
- **Unified Theming** - Consistent visual language across all applications
- **Custom Branding** - VOS identity integrated throughout the system
- **Photography-Optimized** - Color-accurate displays and professional photo editing tools

### ⚡ Workflow Efficiency
- **Dual Window Manager Support** - Switch between Niri and Hyprland seamlessly
- **Web Applications Integration** - Native-feeling web apps with custom keybindings
- **Ghostty Terminal** - Modern, GPU-accelerated terminal experience
- **Gaming Optimized** - Performance tweaks and gaming-specific configurations

### 🔧 Technical Foundation
- **Arch Linux Base** - Rolling release with latest packages
- **Wayland Native** - Modern display protocol for better performance
- **Modular Configuration** - Easy to customize and maintain
- **Automated Installation** - Scripts for quick setup and deployment

## 📁 Project Structure

```
VOS-Desktop/
├── 📚 docs/                    # Comprehensive documentation
│   ├── installation.md         # Step-by-step installation guide
│   ├── configuration.md        # Configuration explanations
│   ├── theming.md              # Theming and customization
│   ├── workflow.md             # Workflow optimization
│   └── troubleshooting.md      # Common issues and solutions
├── ⚙️ configs/                 # Configuration files
│   ├── niri/                   # Niri window manager configs
│   ├── hyprland/               # Hyprland window manager configs
│   ├── noctalia/               # Noctalia shell configs
│   └── shared/                 # Shared configurations
├── 🔧 scripts/                 # Installation and utility scripts
│   ├── install.sh              # Main installation script
│   ├── package-manager.sh      # Package installation management
│   └── theme-switcher.sh       # Theme switching utilities
├── 🎨 themes/                  # Theme files and customizations
├── 🖼️ assets/                  # Icons, wallpapers, and media
├── 🌐 webapps/                 # Web application configurations
└── 📦 packages/                # Package lists and management
```

## 🚀 Quick Start

### Prerequisites
- Fresh Arch Linux installation
- Internet connection
- Basic familiarity with terminal

### Installation
```bash
# Clone the repository
git clone https://github.com/Crowdrocker/VOS-Desktop.git
cd VOS-Desktop

# Run the installation script
chmod +x scripts/install.sh
./scripts/install.sh
```

### Choose Your Window Manager
```bash
# For Niri (Recommended for productivity)
./scripts/setup-niri.sh

# For Hyprland (Recommended for gaming)
./scripts/setup-hyprland.sh

# Or install both for maximum flexibility
./scripts/setup-both.sh
```

## 📖 Documentation

| Document | Description |
|----------|-------------|
| [Installation Guide](docs/installation.md) | Complete setup instructions |
| [Configuration Guide](docs/configuration.md) | Detailed configuration explanations |
| [Theming Guide](docs/theming.md) | Customization and theming |
| [Workflow Guide](docs/workflow.md) | Productivity tips and workflows |
| [Troubleshooting](docs/troubleshooting.md) | Common issues and solutions |

## 🎮 Optimized For

### 📸 Photography Workflow
- Color-accurate display calibration
- Professional photo editing suite (GIMP, Darktable, RawTherapee)
- Efficient file management and organization
- Hardware acceleration for image processing

### 🎯 Gaming Performance
- Low-latency input handling
- Optimized graphics drivers
- Gaming-specific kernel parameters
- Steam and Lutris integration

### 💼 Professional Development
- Multiple monitor support
- Efficient window management
- Development tools and IDEs
- Version control integration

## 🌐 Web Applications

VOS Desktop includes seamless integration of web applications that feel native to the system:

- **Communication**: Discord, Slack, Teams
- **Productivity**: Notion, Todoist, Google Workspace
- **Development**: GitHub, GitLab, Figma
- **Media**: Spotify, YouTube Music, Netflix

All web apps are accessible through custom keybindings and integrate with the system theme.

## 🎨 Theming Philosophy

Our theming approach follows these principles:

1. **Consistency** - Unified visual language across all applications
2. **Functionality** - Beautiful designs that enhance usability
3. **Customization** - Easy to modify and personalize
4. **Performance** - Lightweight themes that don't impact system performance

## 🤝 Inspiration & Credits

This project stands on the shoulders of giants:

- **[Jakoolit](https://github.com/JaKooLit)** - Exceptional theming and visual design inspiration
- **[Omarchy](https://github.com/omarchy)** - Workflow efficiency and functional design patterns
- **Niri Community** - Innovative window management concepts
- **Hyprland Community** - Performance and gaming optimizations

## 🔧 Customization

VOS Desktop is designed to be highly customizable:

```bash
# Switch themes
./scripts/theme-switcher.sh

# Modify keybindings
vim configs/shared/keybindings.conf

# Add new web applications
./scripts/add-webapp.sh

# Update package lists
./scripts/package-manager.sh update
```

## 📊 System Requirements

### Minimum Requirements
- **CPU**: 64-bit processor
- **RAM**: 4GB (8GB recommended)
- **Storage**: 20GB free space
- **Graphics**: Any GPU with Wayland support

### Recommended for Photography
- **RAM**: 16GB or more
- **Storage**: SSD with 50GB+ free space
- **Graphics**: Dedicated GPU with 4GB+ VRAM
- **Display**: Color-accurate monitor

### Recommended for Gaming
- **CPU**: Modern multi-core processor
- **RAM**: 16GB or more
- **Graphics**: Dedicated gaming GPU
- **Storage**: NVMe SSD

## 🐛 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links

- **GitHub Repository**: [https://github.com/Crowdrocker](https://github.com/Crowdrocker)
- **Documentation**: [docs/](docs/)
- **Issues**: [GitHub Issues](https://github.com/Crowdrocker/VOS-Desktop/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Crowdrocker/VOS-Desktop/discussions)

---

<div align="center">

**Made with ❤️ by [Crowdrocker](https://github.com/Crowdrocker)**

*Combining the best of Jakoolit's theming with Omarchy's workflow efficiency*

</div>
