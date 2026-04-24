- 特性：
  - 装饰器 + 响应式架构
  - MVVM 架构
  - 强大的 API 设计
  - 插件系统 ：支持通过 effects 系统扩展功能
  - 框架支持 ：同时支持 React 和 Vue 框架

## 核心特色

### 1. 高性能设计

- 分布式状态管理 ：每个字段独立管理状态，避免整树渲染，显著提升表单操作性能
- 响应式系统 ：基于@formily/reactive 实现细粒度状态更新，确保只更新必要的组件

### 2. 设计器支持

- 可视化表单构建 ：通过 Form Builder 可视化工具快速开发表单，降低开发成本
- 拖拽式操作 ：支持通过拖拽方式设计复杂表单布局

### 3. 组件生态

- 深度集成 ：内置集成 Ant Design 和 Alibaba Fusion 组件库
- 开箱即用 ：提供丰富的表单组件，无需额外配置即可使用

### 4. 架构优势

- JSON Schema 支持 ：深度集成 JSON Schema 协议，支持后端驱动表单渲染
- 双范式转换 ：支持 JSON Schema（后端）和 JSchema（前端）两种范式相互转换
- 副作用管理 ：独立管理表单副作用，使数据联动更简单直观

### 5. 布局能力

- 灵活布局 ：支持复杂的表单布局场景
- 多种布局组件 ：提供 FormGrid、FormTab、FormStep 等多种布局组件

## 开发

```
# 安装依赖
npm install

# 启动开发服务
npm run start_l
http://localhost:8000

# 测试
npm run test

# 构建库
npm run build

# 构建文档
npm run build:docs
```

## 目录结构

- .github/ # GitHub 相关配置
- .vscode/ # VSCode 配置
- devtools/ # 开发工具
- docs/ # 项目文档
- packages/ # 核心包集合
- .all-contributorsrc # 贡献者配置
- .codecov.yml # Codecov 配置
- .editorconfig # 编辑器配置
- .eslintignore # ESLint 忽略配置
- .eslintrc # ESLint 配置
- .gitignore # Git 忽略配置
- .prettierrc.js # Prettier 配置
- .umirc.js # Umi 配置
- .yarnrc # Yarn 配置
- CHANGELOG.md # 变更日志
- LICENSE.md # 许可证
- README.md # 项目说明
- README.zh-cn.md # 中文项目说明
- commitlint.config.js # Commitlint 配置
- global.config.ts # 全局配置
- jest.config.js # Jest 配置
- lerna.json # Lerna 配置
- package.json # 根包配置

## 开发提交

#### 示例

```
git commit -m "chore: 本地开发"
git commit -m "feat: 本地开发"
git commit -m "fix: 本地开发"
```

#### 类型说明

| 类型     | 说明                     |
| -------- | ------------------------ |
| feat     | 新功能                   |
| fix      | 修复 bug                 |
| chore    | 构建过程或辅助工具的变动 |
| docs     | 文档更新                 |
| style    | 代码风格调整             |
| refactor | 代码重构                 |
| perf     | 性能优化                 |
| test     | 测试相关                 |
| ci       | CI 配置更新              |
| revert   | 回滚代码                 |
