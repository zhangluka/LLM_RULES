# LLM Rules 项目

[![Repository](https://img.shields.io/badge/Repository-LLM_RULES-blue.svg)](https://github.com/zhangluka/LLM_RULES)
[![Language](https://img.shields.io/badge/Language-中文-orange.svg)](https://github.com/zhangluka/LLM_RULES)
[![Framework](https://img.shields.io/badge/Framework-LangGPT-green.svg)](https://github.com/langgptai/LangGPT)

## 📖 项目简介

**LLM Rules** 是一个专注于大语言模型提示词工程和开发规范的开源项目。本项目提供了结构化的角色定义、开发规范和技术指南，帮助开发者更好地与 AI 模型协作，提高开发效率和代码质量。

项目采用 [LangGPT](https://github.com/langgptai/LangGPT) 结构化提示词框架，为不同的开发场景提供标准化的角色定义和工作流程。

## 🏗️ 项目结构

```
LLM_Prompt/
├── roles/                 # 角色定义目录
│   └── prompt_master.md   # Prompt 大师角色定义
├── rules/                 # 开发规范目录
│   └── electron_rule.md   # Electron 开发规范
├── ignore/               # 忽略文件配置
│   └── .cursorignore     # Cursor IDE 忽略配置
└── README.md             # 项目文档
```

## 📁 目录说明

### roles/ - 角色定义

包含各种 AI 角色的结构化提示词定义，采用 LangGPT 框架编写。

- **prompt_master.md**: Prompt 大师角色，精通 LangGPT 结构化提示词框架的专家，能够根据用户需求设计和生成高质量的角色提示词。

### rules/ - 开发规范

包含各类技术栈和开发场景的规范文档。

- **electron_rule.md**: Electron 桌面应用开发全局规范，定义了 Electron + React/TypeScript 项目的技术栈、编码规范、沟通风格和工作流程。

### ignore/ - 忽略配置

包含各种 IDE 和工具的忽略文件配置。

## 🎯 核心特性

### 🤖 结构化提示词

- 基于 LangGPT 框架的标准化提示词结构
- 完整的角色定义：Profile、Goals、Skills、Rules、Workflow 等
- 可直接使用的高质量提示词模板

### 📋 开发规范

- 针对特定技术栈的详细开发指南
- 标准化的编码规范和最佳实践
- 结构化的工作流程和沟通方式

### 🔧 实用工具

- 支持多种主流技术栈（Electron、React、TypeScript 等）
- 提供可直接运行的代码示例
- 包含性能优化和安全加固指导

## 🚀 快速开始

### 使用角色定义

1. 浏览 `roles/` 目录，找到需要的角色定义
2. 根据 LangGPT 框架结构，提取所需的角色提示词
3. 在你的 AI 工具中使用这些提示词来获得更好的交互效果

### 使用开发规范

1. 查看 `rules/` 目录中的相关技术规范
2. 根据你的项目需求选择合适的规范文档
3. 遵循文档中的指导进行开发工作

### 贡献新的角色或规范

欢迎为项目贡献新的角色定义或开发规范！

## 📝 使用示例

### Prompt 大师角色使用

```markdown
# Role: Prompt 大师

## Profile

- Author: LangGPT
- Version: 2.0
- Language: 中文
- Description: 精通 LangGPT 结构化提示词框架的专家

## Initialization

你好！我是 **Prompt 大师**，精通 LangGPT 结构化提示词框架。
我能够根据你的需求，生成符合 LangGPT 规范的高质量角色提示词。
```

### Electron 开发规范使用

```markdown
## Core Technology Stack

- **框架**：Electron、React、TypeScript、Next.js App Router
- **UI 库**：Shadcn UI、Tailwind CSS、Ant Design、Mantine
- **包管理工具**：pnpm

## Coding Standards

- 使用最新稳定版本的 TypeScript/JavaScript/React/Node.js
- 完整实现所有功能，不偷懒，不省略代码
- 类型安全优先，充分利用 TypeScript 类型系统
```

## 🤝 贡献指南

我们欢迎社区贡献！贡献方式包括：

1. **新增角色定义**：为新的应用场景创建 LangGPT 格式的角色提示词
2. **完善开发规范**：为不同的技术栈添加详细的开发指南
3. **改进现有内容**：优化现有的角色定义和规范文档
4. **提交 Issue**：报告问题或提出改进建议

### 贡献流程

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 🙏 致谢

- [LangGPT](https://github.com/langgptai/LangGPT) - 结构化提示词框架
- 所有贡献者和社区成员

## 🔗 相关链接

- **项目主页**: https://github.com/zhangluka/LLM_RULES
- **LangGPT 框架**: https://github.com/langgptai/LangGPT
- **最新版本**: [![GitHub release](https://img.shields.io/github/v/release/zhangluka/LLM_RULES.svg)](https://github.com/zhangluka/LLM_RULES/releases)

---

**💡 提示**: 本项目持续更新中，欢迎关注和贡献！
