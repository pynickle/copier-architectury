# 🎮 Copier Architectury Template

A modern Copier template for creating Minecraft mods using the Architectury loom, designed to streamline your mod development workflow.

## ✨ Features

- **Minecraft Version Support**: Currently supports 1.21.1
- **Multi-loader Support**: Built-in support for Fabric and NeoForge
- **Architectury Framework**: Uses Architectury loom for cross-loader mod development
- **Modern Project Structure**: Clean, organized codebase with common and loader-specific modules
- **Mixin Support**: Comes with ready-to-use mixin configurations
- **License Configuration**: Support for multiple open-source licenses

## 📋 Prerequisites

### 📦 Install Copier

Using uv:
```shell
uv tool install copier --with copier-templates-extensions
```

Or using pipx:
```shell
pipx install copier
pipx inject copier copier-templates-extensions
```

## 🚀 Usage

Generate a new Minecraft architectury mod project using this template:

```bash
copier copy --trust "gh:pynickle/copier-architectury" {your_project_path}
```

## 🔮 Future Plans

- Support for additional Minecraft versions
- Optional Architectury API inclusion for cross-loader compatibility
- Optional Fabric API integration for Fabric loader
- Optional Semantic Release Minecraft integration for automated mod publishing
- Choose which mod loaders to support during project initialization
- Enhanced configuration options for mod dependencies

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy modding! 🎮
