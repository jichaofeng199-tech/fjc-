# 变更日志

本文档记录 Progressive Doc Generator 的所有重要变更。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)，
版本号遵循 [语义化版本](https://semver.org/lang/zh-CN/)。

## [未发布]

### 计划中
- 添加更多编程语言支持（Rust、Go 等）
- 支持自动生成 UML 图
- 添加文档版本管理功能
- 支持多语言文档生成

---

## [1.0.0] - 2026-03-28

### 新增
- ✨ 初始版本发布
- 📝 完整的 SKILL.md 文档
- 🎨 YAML front matter 元数据支持
- 📚 5 个标准文档模板
  - `template_readme.md` - README学习指南模板
  - `template_project_overview.md` - 项目概览模板
  - `template_api.md` - API接口模板
  - `template_module.md` - 模块文档模板
  - `template_examples.md` - 使用示例模板
- 🔧 2 个辅助工具脚本
  - `doc_validator.py` - 文档质量检查工具
  - `structure_analyzer.py` - 项目结构分析工具
- ⚙️ 完整的 `config.yaml` 配置文件
- 📖 详细的 README.md 文档
- 💡 最佳实践文档 `best-practices.md`
- 🎯 示例项目 `simple_project/`
  - 完整的 C++ 项目结构
  - CMake 构建配置
  - 工具函数实现

### 文档结构
- 📁 `references/` - 文档模板目录
- 📁 `scripts/` - 辅助工具脚本目录
- 📁 `examples/` - 示例项目目录
- 📄 `config.yaml` - 配置文件
- 📄 `README.md` - 项目说明文档
- 📄 `best-practices.md` - 最佳实践文档
- 📄 `CHANGELOG.md` - 变更日志

### 核心特性
- 🎯 渐进式披露原则
- 📊 基于实际代码的文档生成
- 💻 完整可运行的代码示例
- 🔄 统一的文档格式和风格
- ✅ 自动化的文档质量检查
- 🔍 智能的项目结构分析

### 配置选项
- 📝 输出目录配置
- 🏗️ 文档结构配置
- 📄 内容生成配置
- 🎨 模板配置
- ✅ 验证配置
- ⚙️ 生成配置
- 📊 分析配置
- 🎨 格式配置
- 🚀 高级配置
- 🐛 调试配置

### 支持的项目类型
- C++ 项目
- Python 项目
- Java 项目
- JavaScript/TypeScript 项目

---

## 版本说明

### 版本号格式
- 主版本号：不兼容的 API 修改
- 次版本号：向下兼容的功能性新增
- 修订号：向下兼容的问题修正

### 变更类型
- `新增` - 新增功能
- `变更` - 功能变更
- `弃用` - 即将在未来版本中移除的功能
- `移除` - 已移除的功能
- `修复` - 问题修复
- `安全` - 安全性相关的修复

---

## 贡献指南

欢迎贡献代码、报告问题或提出改进建议！

### 如何贡献
1. Fork 本项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

### 变更日志规范
- 所有重大变更都应记录在 CHANGELOG.md 中
- 变更记录应包含变更类型、描述和影响
- 遵循 Keep a Changelog 格式规范

---

## 许可证

本项目遵循项目许可证要求。

---

**最后更新**: 2026-03-28
**当前版本**: 1.0.0
**维护者**: AI Assistant
