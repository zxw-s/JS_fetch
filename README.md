# JS Fetch Demo

原生 JavaScript **Fetch API** 网络请求练习项目，实现 GET/POST 数据请求、JSON 数据解析与页面渲染。纯前端、零框架。

## 📁 目录结构

```Plain
js-fetch-demo/
├── index.html      # 主页面
├── css/
│   └── style.css   # 样式
├── js/
│   └── main.js     # fetch 请求逻辑
└── README.md
```

## ✨ 项目功能

- 使用原生 `fetch` 发送网络请求

- 解析 JSON 接口数据

- 异步获取数据并动态渲染 DOM

- 捕获请求异常与错误处理

## 🚀 运行方式

**必须使用本地服务器运行（禁止直接双击打开）**

fetch 属于跨域安全接口，`file://` 协议会报错

```bash
# Python 快速启动
python -m http.server 8080# 或 Nodenpx serve .
```

访问：`http://localhost:8080`

## 🧩 核心技术点

- `async / await` 异步语法

- `fetch()` 发起 HTTP 请求

- `.json()` 解析响应数据

- `try / catch` 请求错误捕获

## ❌ 常见问题

- **CORS 跨域错误**：接口服务未开启跨域，更换公开测试接口或后端配置跨域

- **404**：请求地址路径错误

- **请求失败**：网络问题、接口地址失效、服务器未开启

## 📄 开源协议

MIT
