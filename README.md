# Bun Starter Template

一个简洁的 Bun 项目模板，包含 TypeScript 和 ESLint 配置。

## 特性

- **Bun** - 快速的 JavaScript 运行时
- **TypeScript** - 启用严格模式，目标为 ESNext
- **ESLint** - 使用 [@antfu/eslint-config](https://github.com/antfu/eslint-config) 保持代码风格一致
- **VSCode** - 预配置保存时自动修复

## 快速开始

### 使用模板

点击 GitHub 上的 "Use this template" 按钮，或者：

```bash
# 创建公开仓库
gh repo create my-project --template Math-chen/bun-starter --public

# 或创建私有仓库
gh repo create my-project --template Math-chen/bun-starter --private

cd my-project
bun install
```

### 手动克隆

```bash
git clone https://github.com/Math-chen/bun-starter.git my-project
cd my-project
bun install
```

## 使用方法

```bash
# 运行入口文件
bun run index.ts

# 代码检查
bun run lint

# 代码检查并自动修复
bun run lint:fix
```

## 项目结构

```
.
├── index.ts           # 入口文件
├── package.json       # 依赖和脚本
├── tsconfig.json      # TypeScript 配置
├── eslint.config.ts   # ESLint 配置
└── .vscode/           # VSCode 设置
```

## 许可证

MIT
