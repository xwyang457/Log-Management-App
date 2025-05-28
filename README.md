# 📘 React Log Management App

A simple log management tool built with React. It supports creating, displaying, deleting, and filtering logs.  
一个用 React 构建的简单日志管理工具，支持创建、显示、删除和筛选日志。

---

**🧩 Features | 功能亮点**

- ✅ Add logs (with date, description, and time spent)  
  添加日志（包括日期、描述和耗时）
- 🗑️ Delete logs with confirmation modal  
  删除日志（带确认弹窗）
- 🔍 Filter logs by keyword  
  根据关键词过滤日志
- 🗓️ Custom date formatting component  
  自定义日期格式组件
- 🧱 Modularized and reusable component structure  
  模块化、可复用的组件结构



**📁 Project Structure | 项目结构**

```text
├── public/
│   └── index.html
├── src/
│   ├── App.js                   # Log app root | 应用入口
│   ├── index.js                # Entry point | React 渲染入口
│   ├── index.css               # Global styles | 全局样式
│   ├── components/
│   │   ├── Logs.js              # Log container | 日志容器
│   │   ├── LogItem.js           # Single log item | 单条日志
│   │   ├── LogsForm.js          # New log form | 新增日志表单
│   │   ├── LogFilter.js         # Filter component | 日志筛选组件
│   │   ├── MyDate.js            # Custom date renderer | 自定义日期组件
│   │   ├── UI/
│   │   │   ├── Card.js          # Card wrapper | 卡片组件
│   │   │   ├── Backdrop.js      # Overlay mask | 背景遮罩
│   │   │   └── ConfirmModal.js  # Confirm dialog | 确认对话框
├── package.json
└── yarn.lock
```
---


**🛠️ Getting Started | 启动项目**

1️⃣ Install dependencies | 安装依赖

```bash
yarn install
# or
npm install

2️⃣ Start development server | 启动开发服务器
```bash
yarn start
# or
npm start


**🖼️ Preview | 项目预览**

The UI includes:
Input forms
A log list
A filter bar

界面包括：
输入表单
日志列表
筛选栏


