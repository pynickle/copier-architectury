# 🎮 Copier Architectury 模板

[English](README.md) | 简体中文

一个现代化的 [Copier](https://github.com/copier-org/copier) 模板，用于使用 Architectury loom 创建 Minecraft 模组，旨在简化您的模组开发工作流程。

## ✨ 特性

- **Minecraft 版本支持**：目前支持 1.21.1
- **多加载器支持**：内置支持 Fabric 和 NeoForge
- **Architectury 框架**：使用 Architectury loom 进行跨加载器模组开发
- **现代化项目结构**：清晰、有序的代码库，包含公共模块和加载器特定模块
- **Gradle 构建系统**：自动化构建和依赖管理
- **许可证配置**：支持多种开源许可证

## 📋 先决条件

### 📦 安装 Copier

使用 uv：
```shell
uv tool install copier --with copier-templates-extensions
```

或使用 pipx：
```shell
pipx install copier
pipx inject copier copier-templates-extensions
```

## 🚀 使用方法

使用此模板生成新的 Minecraft architectury 模组项目：

```bash
copier copy --trust "gh:pynickle/copier-architectury" {your_project_path}
```

## 🔮 未来计划

- 支持更多 Minecraft 版本
- 可选的 Architectury API 包含，用于跨加载器兼容性
- 可选的 Fabric API 集成，用于 Fabric 加载器
- 可选的 Semantic Release Minecraft 集成，用于自动化模组发布
- 支持在项目初始化时选择要支持的加载器
- 增强的模组依赖配置选项

## ⚖️ 许可证

本项目采用 MIT 许可证 - 详情请参阅 [LICENSE](LICENSE) 文件。

祝您模组开发愉快！🎮
