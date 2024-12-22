# Vue3 移动端购物车项目

## 项目介绍

  该项目是一个基于 **Vite** 和 **Vue 3** 创建的移动端网页购物车应用，提供了常见的电商功能，包括商品列表展示、商品详情查看、购物车的增删改查（CRUD）、用户注册和登录、头像上传等功能。

### 主要功能：

- 商品列表展示与浏览
- 商品详情页面
- 购物车增删改查（商品添加、删除、数量调整）
- 用户注册与登录
- 头像上传功能

## 技术栈

- **前端：**
  - Vue 3（选项式 API）
  - TypeScript（TS）
  - Vite（构建工具）
  - Pinia（状态管理）
  - Vue Router（路由管理）
  - Sass（样式）
  
- **工具与依赖：**
  - **pnpm**：依赖管理工具
  - **ESLint**：代码质量检查

## 项目运行

### 安装依赖

1. 克隆项目到本地：
   ```bash
   git clone <repository_url>

2. 进入项目目录：
  ```bash
  cd <project_directory>

1. 安装依赖：
  ```bash
   pnpm install

### 启动开发环境
  ```bash
   pnpm dev
  ```

  启动后，项目会在浏览器中自动打开（默认 http://localhost:5173），你可以开始开发或测试。

#### 打包项目

   ```bash
   pnpm build
   ```

  打包后的文件将存储在 dist 目录中，可以将其部署到生产环境中。

#### 代码检查

  ```bash
   pnpm lint
  ```

  该命令将使用 ESLint 检查代码中的潜在问题。

#### **注意事项：**

- 目前项目的 接口 尚未完善，因此登录、注册和头像上传等功能暂时无法正常使用。后续计划使用 Node.js 编写接口来解决这些问题。
- 商品列表和购物车的逻辑已经实现，但由于缺少后端接口，无法完成与服务器的交互。

## 后续计划

- **接口开发：**
  - 计划使用 Node.js 完成后端接口的开发，支持商品数据、用户注册登录、购物车增删改查等功能。
  - 优化功能：完善用户体验，优化界面和交互效果，确保适配不同设备。
  - 测试与部署：对项目进行全面测试，确保前后端的无缝对接，部署到生产环境。