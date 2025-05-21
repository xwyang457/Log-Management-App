📘 React Log Management App

A simple log management tool built with React. It supports creating, displaying, deleting, and filtering logs.

🧩 Features

Add logs (with date, description, and time spent)

Delete logs with confirmation modal

Filter logs by keyword

Custom date formatting component

Modularized and reusable component structure

📁 Project Structure
csharp
Copy
Edit
├── public/
│   └── index.html               
├── src/
│   ├── App.js                   
│   ├── index.js                
│   ├── index.css               
│   ├── components/
│   │   ├── Logs.js              # 日志容器
│   │   ├── LogItem.js           # 单条日志
│   │   ├── LogsForm.js          # 新增日志表单
│   │   ├── LogFilter.js         # 日志筛选组件
│   │   ├── MyDate.js            # 自定义日期组件
│   │   ├── UI/
│   │   │   ├── Card.js          # 卡片组件
│   │   │   ├── Backdrop.js      # 背景遮罩
│   │   │   └── ConfirmModal.js  # 确认对话框
├── package.json
└── yarn.lock
🛠️ 启动项目 | Getting Started
安装依赖 Install dependencies
bash
Copy
Edit
yarn install
# 或者使用 npm:
# npm install
启动开发服务器 Start development server
bash
Copy
Edit
yarn start
# 或者使用 npm:
# npm start
🖼️ 项目预览 | Preview
示例界面包括输入表单、日志列表与筛选栏等。

The UI includes input forms, a log list, and a filter bar.
