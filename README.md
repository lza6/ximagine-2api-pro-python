<![CDATA[<div align="center">

# 🎬 Ximagine-2API Pro Python

<img src="https://img.shields.io/badge/version-2.2.0-blue?style=for-the-badge&logo=python&logoColor=white" alt="Version">
<img src="https://img.shields.io/badge/license-Apache%202.0-green?style=for-the-badge" alt="License">
<img src="https://img.shields.io/badge/python-3.8+-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/platform-Windows-lightgray?style=for-the-badge&logo=windows&logoColor=white" alt="Platform">

**✨ 一款开箱即用的 AI 视频生成桌面应用 ✨**

*基于 Ximagine API 的本地化代理服务，提供赛博朋克风格 UI 和一键启动体验*

[🚀 快速开始](#-一键启动教程懒人专用) • [📖 功能介绍](#-主要功能) • [🔧 技术原理](#-核心技术原理详解) • [🛣️ 发展路线](#️-未来发展路线图)

---

</div>

## 📣 项目简介

> 🎉 **你好，开发者/小白朋友！** 欢迎来到这个充满科技感的 AI 视频生成世界！

这个项目是什么呢？简单来说：

```
你输入一句话 ➜ 点击按钮 ➜ 🎥 一段 AI 视频就生成出来了！
```

**举个栗子 🌰：**
- 你输入：`一只可爱的柯基在草地上奔跑`
- AI 会为你生成一段 5 秒左右的高清视频！

**它的核心价值：**
- 🎯 **极简体验**：双击运行，无需任何配置
- 🖥️ **桌面应用**：独立窗口，不依赖浏览器
- 🔐 **隐私安全**：本地运行，数据不留痕
- 🎨 **颜值在线**：赛博朋克 UI，四款炫酷主题

---

## 🎯 这个项目能做什么？（使用场景）

| 场景 | 描述 | 适合人群 |
|------|------|----------|
| 🎬 短视频创作 | 快速生成创意视频素材 | 短视频博主、内容创作者 |
| 📱 社交媒体 | 制作吸引眼球的视频封面/预告 | 新媒体运营 |
| 🎮 游戏/动画 | 快速产出概念视频 | 游戏开发者、动画师 |
| 📚 教学演示 | 生成教学辅助视频 | 教师、培训师 |
| 🧪 技术研究 | 研究 AI 视频生成技术 | 开发者、研究人员 |
| 🎁 个人娱乐 | 把自己的创意变成视频！ | 所有人！ |

---

## ✨ 主要功能

### 🎨 视频生成模式

| 模式 | 模型 ID | 说明 | 效果 |
|------|---------|------|------|
| 📽️ 标准现实 | `grok-video-normal` | 真实风格视频生成 | ⭐⭐⭐⭐⭐ |
| 🎭 趣味卡通 | `grok-video-fun` | 卡通动画风格 | ⭐⭐⭐⭐ |
| 🔥 激情模式 | `grok-video-spicy` | 更具表现力的风格 | ⭐⭐⭐⭐ |
| 🖼️ 图生视频 | `grok-video-image` | 上传图片生成视频 | ⭐⭐⭐⭐⭐ |
| 🎨 文生图 | `grok-image` | 文字描述生成图片 | ⭐⭐⭐⭐ |

### 📐 画面比例支持

- **1:1** - 方形（适合社交媒体头像/封面）
- **16:9** - 横屏（适合 YouTube、B站视频）
- **9:16** - 竖屏（适合抖音、小红书）

### 🎨 四款炫酷主题

1. **Cyberpunk** 💜 - 经典赛博朋克（霓虹蓝+霓虹粉）
2. **Matrix** 💚 - 黑客帝国风格（经典绿色终端）
3. **Golden** 🌟 - 奢华金色主题（尊贵典雅）
4. **Clean** 🤍 - 清爽白色模式（护眼首选）

---

## 🚀 一键启动教程（懒人专用）

> 🎁 **好消息**：你无需安装 Python！脚本会自动帮你搞定一切！

### 方法一：超级懒人版 (推荐 ⭐⭐⭐⭐⭐)

```bash
# 第一步：下载项目
git clone https://github.com/lza6/ximagine-2api-pro-python.git

# 第二步：进入目录
cd ximagine-2api-pro-python

# 第三步：双击运行！
run.bat
```

**就这么简单！** 😎

启动器会自动完成：
1. ✅ 检测系统是否有 Python
2. ✅ 没有的话自动下载嵌入式 Python
3. ✅ 自动安装所有依赖库
4. ✅ 启动应用程序

### 方法二：手动安装版

如果你已经有 Python 环境，也可以手动安装：

```bash
# 1. 克隆项目
git clone https://github.com/lza6/ximagine-2api-pro-python.git
cd ximagine-2api-pro-python

# 2. 创建虚拟环境（可选但推荐）
python -m venv venv
venv\Scripts\activate  # Windows
# 或 source venv/bin/activate  # Mac/Linux

# 3. 安装依赖
pip install -r requirements.txt

# 4. 运行程序
python main.py
```

---

## 🎮 使用教程（小白友好版）

### Step 1️⃣ 启动程序

双击 `run.bat`，等待窗口打开

### Step 2️⃣ 熟悉界面

```
┌─────────────────────────────────────────────────────────┐
│  左侧: 控制面板                    右侧: 作品展示区      │
│  ├─ API 信息                      ├─ 生成中的任务        │
│  ├─ 画面比例选择                   ├─ 已完成的视频        │
│  ├─ 视频风格选择                   └─ 历史记录            │
│  ├─ 图片上传区                                           │
│  └─ 提示词输入框                                         │
└─────────────────────────────────────────────────────────┘
```

### Step 3️⃣ 开始创作

1. 在 **"创意描述"** 框中输入你的想法，比如：
   ```
   一位宇航员在火星表面行走，背景是壮观的红色星球
   ```

2. 选择 **画面比例**（16:9 横屏最常用）

3. 选择 **视频风格**（标准现实效果最佳）

4. （可选）上传一张参考图片

5. 点击 **🚀 开始生成** 按钮

### Step 4️⃣ 等待 & 下载

- 视频通常需要 30-120 秒生成
- 生成完成后会自动显示在右侧
- 点击 **下载** 按钮保存到本地

---

## 🔌 API 使用教程（开发者专属）

本项目提供了兼容 OpenAI 格式的 API 接口，你可以用任何支持 OpenAI API 的客户端调用！

### 📍 API 地址

```
http://127.0.0.1:9527
```

### 🔑 API 密钥

```
1
```
（是的，就是数字 1，默认密钥，可在代码中修改）

### 📝 接口列表

| 端点 | 方法 | 功能 |
|------|------|------|
| `/v1/models` | GET | 获取可用模型列表 |
| `/v1/chat/completions` | POST | 创建生成任务（SSE流式） |
| `/v1/upload` | POST | 上传参考图片 |
| `/v1/query/status` | GET | 查询任务状态 |
| `/v1/proxy/download` | GET | 代理下载视频 |

### 🧪 示例：使用 curl 调用

```bash
# 获取模型列表
curl http://127.0.0.1:9527/v1/models

# 生成视频
curl http://127.0.0.1:9527/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer 1" \
  -d '{
    "model": "grok-video-normal",
    "messages": [{"role": "user", "content": "一只猫在钢琴上弹奏"}],
    "stream": true
  }'
```

### 🐍 示例：Python 调用

```python
import requests
import json

# 创建任务
response = requests.post(
    "http://127.0.0.1:9527/v1/chat/completions",
    headers={
        "Authorization": "Bearer 1",
        "Content-Type": "application/json"
    },
    json={
        "model": "grok-video-normal",
        "messages": [{
            "role": "user",
            "content": json.dumps({
                "prompt": "一只可爱的柯基在沙滩上奔跑",
                "aspectRatio": "16:9",
                "clientPollMode": True  # 异步模式
            })
        }],
        "stream": True
    },
    stream=True
)

# 处理SSE流
for line in response.iter_lines():
    if line:
        print(line.decode())
```

---

## 💎 优点与缺点分析

### ✅ 优点

| 特性 | 说明 | 评分 |
|------|------|------|
| 🚀 开箱即用 | 双击运行，零配置 | ⭐⭐⭐⭐⭐ |
| 🖥️ 独立应用 | 原生窗口，不依赖浏览器 | ⭐⭐⭐⭐⭐ |
| 🎨 UI 美观 | 赛博朋克风格，4 种主题 | ⭐⭐⭐⭐⭐ |
| 🔗 API 兼容 | 支持 OpenAI 格式接口 | ⭐⭐⭐⭐⭐ |
| 🔐 RSA 加密 | 安全的上传鉴权机制 | ⭐⭐⭐⭐⭐ |
| 📡 SSE 流式 | 实时展示生成进度 | ⭐⭐⭐⭐ |
| 🌐 代理下载 | 绕过跨域限制，稳定下载 | ⭐⭐⭐⭐ |
| 💾 智能启动 | 自动环境检测和安装 | ⭐⭐⭐⭐⭐ |

### ⚠️ 缺点/限制

| 限制 | 说明 | 改进建议 |
|------|------|----------|
| 💻 仅限 Windows | 目前只支持 Windows 系统 | 计划支持 Mac/Linux |
| 🌐 需要网络 | 依赖 Ximagine 云端 API | 无法离线使用 |
| ⏱️ 生成时间长 | 视频生成需要 30-120 秒 | 云端算力限制 |
| 💰 依赖第三方 | 依赖 Ximagine 服务可用性 | 计划支持更多后端 |
| 📦 无持久存储 | 刷新页面数据丢失 | 计划增加本地数据库 |

---

## 🔧 核心技术原理详解

> 🧑‍🏫 **小课堂开始！** 下面我用大白话 + 专业术语的方式，带你深入理解这个项目的技术实现～

### 1️⃣ 整体架构

```
┌──────────────────────────────────────────────────────────────┐
│                       用户界面层 (UI Layer)                    │
│  ┌────────────────────────────────────────────────────────┐  │
│  │  PyWebView 原生窗口 (Desktop Window)                   │  │
│  │  └── 内嵌 HTML/CSS/JS (Cyberpunk UI)                   │  │
│  └────────────────────────────────────────────────────────┘  │
│                              ↓                                │
│                        HTTP 请求                               │
│                              ↓                                │
├──────────────────────────────────────────────────────────────┤
│                      后端服务层 (Backend Layer)                │
│  ┌────────────────────────────────────────────────────────┐  │
│  │  Flask Web Server (端口 9527)                          │  │
│  │  ├── /v1/models          - 模型列表                    │  │
│  │  ├── /v1/chat/completions - 生成任务                    │  │
│  │  ├── /v1/upload          - 图片上传                    │  │
│  │  ├── /v1/query/status    - 状态查询                    │  │
│  │  └── /v1/proxy/download  - 代理下载                    │  │
│  └────────────────────────────────────────────────────────┘  │
│                              ↓                                │
│                        HTTP 代理                               │
│                              ↓                                │
├──────────────────────────────────────────────────────────────┤
│                      上游服务层 (Upstream)                     │
│  ┌────────────────────────────────────────────────────────┐  │
│  │  Ximagine API (https://api.ximagine.io)                │  │
│  │  └── AI 视频/图像生成服务                               │  │
│  └────────────────────────────────────────────────────────┘  │
└──────────────────────────────────────────────────────────────┘
```

### 2️⃣ 核心技术点详解

#### 🔹 Flask（Web 框架）
```python
from flask import Flask, request, jsonify, Response
app = Flask(__name__)
```
**白话解释**：Flask 就像一个"服务员"，负责接收你的请求（比如"我要生成视频"），然后把结果返回给你。

**专业解释**：Flask 是一个轻量级 WSGI Web 应用框架，采用 Werkzeug 作为 HTTP 工具集，Jinja2 作为模板引擎。

**难度评级**：⭐⭐（入门级，Python Web 开发必学）

---

#### 🔹 PyWebView（桌面窗口）
```python
import webview
webview.create_window("APP名称", "http://127.0.0.1:9527", width=1498, height=1739)
webview.start()
```
**白话解释**：PyWebView 让你的网页可以像一个真正的桌面软件一样运行，有自己的窗口，不需要打开浏览器。

**专业解释**：PyWebView 是一个跨平台库，使用系统原生 WebView 组件（Windows 上是 Edge WebView2）来渲染 HTML 内容。

**难度评级**：⭐⭐（简单易用）

---

#### 🔹 RSA 非对称加密（上传鉴权）
```python
from cryptography.hazmat.primitives.asymmetric import padding
encrypted = public_key.encrypt(
    payload.encode(),
    padding.OAEP(mgf=padding.MGF1(algorithm=hashes.SHA256()), ...)
)
```
**白话解释**：这就像一个"密码锁"。你用公钥把数据锁起来，只有服务器有私钥能打开。

**专业解释**：使用 RSA-OAEP（Optimal Asymmetric Encryption Padding）算法进行非对称加密，结合 SHA-256 哈希函数，确保上传请求的身份验证和数据完整性。

**难度评级**：⭐⭐⭐⭐（需要密码学基础）

---

#### 🔹 SSE（Server-Sent Events 服务端推送）
```python
def generate():
    yield f"data: {json.dumps(chunk)}\n\n"
return Response(stream_with_context(generate()), mimetype='text/event-stream')
```
**白话解释**：服务器可以像"直播"一样，一点一点地把生成进度推送给你，而不是等全部完成才返回。

**专业解释**：SSE 是一种基于 HTTP 的单向服务器推送技术，服务器通过 `text/event-stream` MIME 类型持续发送数据到客户端。

**难度评级**：⭐⭐⭐（需要理解流式响应）

---

#### 🔹 指纹伪装（Anti-Detection）
```python
def generate_identity():
    ip = f"{random.randint(1,254)}.{random.randint(1,254)}.{...}"
    ua = f"Mozilla/5.0 ... Chrome/{random.randint(128,132)}.0.{random.randint(6000,7000)}.0 ..."
    return {"ip": ip, "ua": ua}
```
**白话解释**：每次请求都伪装成不同的"身份"，让服务器认为是来自不同地方、不同浏览器的真人在访问。

**专业解释**：通过随机生成 IP 地址、User-Agent、Chrome 版本等请求头信息，模拟真实浏览器指纹，绕过反爬虫机制。

**难度评级**：⭐⭐⭐（需要了解 HTTP 协议和反爬虫知识）

---

#### 🔹 异步轮询机制
```python
# 客户端模式：立即返回任务 ID
if client_poll_mode:
    return f"[TASK_ID:{task_id}|UID:{unique_id}|TYPE:video]"

# 客户端定时查询状态
setInterval(() => fetch('/v1/query/status?taskId=' + id), 2000);
```
**白话解释**：你提交任务后，不用一直等着。程序会给你一个"任务号"，然后你每隔 2 秒去问一下"我的视频好了没"。

**专业解释**：采用异步任务队列 + 客户端轮询模式，将长时间的视频生成任务解耦为：任务创建（同步）+ 状态查询（异步轮询）。

**难度评级**：⭐⭐⭐（需要理解异步编程模式）

---

#### 🔹 代理下载（绕过跨域限制）
```python
@app.route('/v1/proxy/download')
def proxy_download():
    req = requests.get(url, headers=headers, stream=True)
    return Response(stream_with_context(req.iter_content(chunk_size=1024)))
```
**白话解释**：视频文件可能在别的服务器上，浏览器不让你直接下载。我们让服务器"代劳"，把视频先下载下来再给你。

**专业解释**：通过后端代理转发请求，绕过浏览器 CORS（跨域资源共享）限制，同时添加正确的 Referer 头以通过服务器端的来源验证。

**难度评级**：⭐⭐⭐（需要理解跨域原理）

---

### 3️⃣ 技术栈一览

| 层级 | 技术 | 用途 | 学习资源 |
|------|------|------|----------|
| 前端 | HTML5 + CSS3 | 页面结构和样式 | MDN Web Docs |
| 前端 | JavaScript ES6+ | 交互逻辑 | JavaScript.info |
| 后端 | Flask 2.3+ | Web 服务框架 | Flask 官方文档 |
| 后端 | Requests | HTTP 客户端库 | Requests 文档 |
| 桌面 | PyWebView 4.4+ | 原生窗口封装 | PyWebView Wiki |
| 加密 | Cryptography | RSA 加密 | Cryptography 文档 |
| 启动 | Batch Script | 自动化环境配置 | SS64 CMD 参考 |

---

## 📁 项目文件结构

```
ximagine-2api-python/
│
├── 📄 main.py                      # 🔥 核心主程序 (919行)
│   ├── CONFIG                      #    配置常量 (API地址/密钥/模型映射)
│   ├── XimagineEngine              #    核心引擎类 (指纹生成/RSA加密)
│   ├── /v1/models                  #    模型列表 API
│   ├── /v1/chat/completions        #    生成任务 API (SSE流式)
│   ├── /v1/upload                  #    图片上传 API (RSA鉴权)
│   ├── /v1/query/status            #    状态查询 API
│   ├── /v1/proxy/download          #    代理下载 API
│   ├── index()                     #    完整的 Cyberpunk UI HTML
│   └── __main__                    #    程序入口 (Flask + WebView)
│
├── 📄 requirements.txt             # 📦 Python 依赖清单
│   ├── flask>=2.3.0                #    Web 框架
│   ├── flask-cors>=4.0.0           #    跨域支持
│   ├── requests>=2.31.0            #    HTTP 客户端
│   ├── pywebview>=4.4.0            #    桌面窗口
│   └── cryptography>=41.0.0        #    RSA 加密
│
├── 📄 run.bat                      # 🚀 智能启动脚本 (260行)
│   ├── 环境检测                     #    检查系统/嵌入式 Python
│   ├── 自动下载                     #    下载嵌入式 Python 3.11.9
│   ├── 依赖安装                     #    pip install requirements.txt
│   ├── 标记文件                     #    .env_ready 极速启动
│   └── 运行主程序                   #    python main.py
│
├── 📄 .env_ready                   # ✅ 环境就绪标记 (自动生成)
├── 📄 ximagine_data.json           # 💾 数据持久化文件 (自动生成)
│
├── 📁 venv/                        # 🐍 Python 虚拟环境 (自动生成)
├── 📁 python/                      # 🐍 嵌入式 Python (按需自动下载)
├── 📁 main.build/                  # 🔨 Nuitka 构建缓存
└── 📁 main.dist/                   # 📦 Nuitka 打包输出

```

### 文件详解

| 文件 | 行数 | 说明 | 核心代码 |
|------|------|------|----------|
| `main.py` | 919 | 主程序 | Flask 路由 + UI + 业务逻辑 |
| `run.bat` | 260 | 启动脚本 | 环境检测 + 自动安装 |
| `requirements.txt` | 7 | 依赖清单 | 5 个核心库 |

---

## 🛣️ 未来发展路线图

### 📍 Phase 1: 功能完善 (进行中)

- [ ] 🔄 添加任务队列管理（批量生成）
- [ ] 💾 增加 SQLite 本地数据库持久化
- [ ] 📊 生成历史统计图表
- [ ] 🔔 系统托盘最小化
- [ ] ⚙️ 设置界面（自定义 API 密钥/端口）

### 📍 Phase 2: 平台扩展

- [ ] 🍎 macOS 支持
- [ ] 🐧 Linux 支持
- [ ] 📱 Web 版本（可部署到云端）
- [ ] 🐳 Docker 容器化

### 📍 Phase 3: 能力增强

- [ ] 🎬 视频拼接/剪辑功能
- [ ] 🎵 背景音乐添加
- [ ] 📝 字幕生成
- [ ] 🔗 多模型后端支持（Runway、Pika 等）

### 📍 Phase 4: 生态建设

- [ ] 📦 插件系统
- [ ] 🌐 社区作品分享
- [ ] 🏪 提示词市场

---

## 🔴 当前不足 & 待改进

> 💡 **开发者们注意！** 这里是你们可以贡献的地方～

### ⚠️ 已知问题

| 问题 | 描述 | 优先级 | 建议解决方案 |
|------|------|--------|-------------|
| 🔄 数据丢失 | 刷新页面后任务和历史消失 | 🔴 高 | 使用 localStorage 或 SQLite |
| ⏳ 超时处理 | 长任务可能超时失败 | 🟡 中 | 增加重试机制 |
| 📱 移动端 | UI 在小屏幕显示不佳 | 🟡 中 | 响应式 CSS 优化 |
| 🔐 密钥暴露 | API Key 硬编码在前端 | 🟢 低 | 添加密钥管理界面 |

### 📋 待实现功能

| 功能 | 描述 | 技术路径 |
|------|------|----------|
| 任务队列 | 批量提交任务排队执行 | 使用 `queue.Queue` + 后台线程 |
| 断点续传 | 下载大文件时支持续传 | Range 请求头 + 分块下载 |
| 日志系统 | 详细的运行日志 | Python `logging` 模块 |
| 单元测试 | 自动化测试覆盖 | `pytest` + `unittest` |
| CI/CD | 自动构建和发布 | GitHub Actions |

---

## 🧩 如何扩展开发

### 添加新模型

1. 在 `CONFIG["MODEL_MAP"]` 中添加模型定义：
```python
"你的模型ID": {
    "type": "video",  # 或 "image"
    "mode": "normal",
    "channel": "YOUR_CHANNEL",
    "pageId": 123,
    "name": "模型显示名称"
}
```

2. 前端 UI 会自动调用 `/v1/models` 获取最新模型列表

### 修改 UI 主题

在 `index()` 函数的 CSS `:root` 中修改颜色变量：
```css
:root {
  --neon-blue: #你的颜色;
  --neon-pink: #你的颜色;
  --bg-dark: #你的颜色;
  /* ... */
}
```

### 添加新 API 端点

```python
@app.route('/v1/your-endpoint', methods=['POST'])
def your_endpoint():
    data = request.json
    # 你的业务逻辑
    return jsonify({"success": True, "data": result})
```

---

## 📊 技术难度评级

| 技术点 | 难度 | 学习时间 | 前置知识 |
|--------|------|----------|----------|
| Flask 基础 | ⭐⭐ | 1-3 天 | Python 基础 |
| HTML/CSS/JS | ⭐⭐ | 3-7 天 | 无 |
| SSE 流式响应 | ⭐⭐⭐ | 1-2 天 | HTTP 协议 |
| RSA 加密 | ⭐⭐⭐⭐ | 2-5 天 | 密码学基础 |
| 异步编程 | ⭐⭐⭐ | 3-5 天 | Python 进阶 |
| PyWebView | ⭐⭐ | 1 天 | GUI 概念 |
| Batch 脚本 | ⭐⭐ | 1-2 天 | Windows 命令行 |

---

## 🤖 AI 爬虫友好指南

> 如果你想用 AI 来分析或复刻这个项目，这里是快速入口：

### 📌 技术蓝图一句话总结

```
Flask Web Server (9527) + PyWebView 桌面封装 
→ Ximagine API 代理 (RSA鉴权 + SSE流式) 
→ Cyberpunk UI (HTML5 + CSS3 + Vanilla JS)
```

### 🗝️ 关键代码入口

| 功能 | 文件 | 行号 | 函数/类 |
|------|------|------|---------|
| 主配置 | main.py | 26-48 | `CONFIG` |
| 指纹生成 | main.py | 74-112 | `XimagineEngine.generate_identity()` |
| RSA 加密 | main.py | 114-139 | `XimagineEngine.encrypt_auth_payload()` |
| 视频生成 | main.py | 265-490 | `chat_completions()` |
| UI 渲染 | main.py | 495-896 | `index()` |
| 程序入口 | main.py | 901-919 | `if __name__ == "__main__"` |
| 智能启动 | run.bat | 1-260 | 完整脚本 |

### 🔄 复刻路径

1. **最小可行版本**：Flask + 一个简单的 `/generate` 端点
2. **添加 UI**：使用 Jinja2 模板或前端 SPA
3. **桌面化**：集成 PyWebView
4. **完善功能**：添加 SSE、轮询、代理下载

---

## 🙏 鸣谢 & 开源精神

> 🌟 **"代码是开源的，但知识是共享的"**

感谢以下开源项目和社区：

- 🐍 [Python](https://python.org) - 优雅的编程语言
- 🔥 [Flask](https://flask.palletsprojects.com) - 简洁的 Web 框架
- 🖥️ [PyWebView](https://pywebview.flowrl.com) - 跨平台桌面封装
- 🔐 [Cryptography](https://cryptography.io) - 强大的加密库
- 🎨 [Font Awesome](https://fontawesome.com) - 精美的图标库

---

<div align="center">

## 🌈 最后的话

```
🎬 让创意变成视频，让想象照进现实
```

如果这个项目对你有帮助，请给个 ⭐ Star 支持一下！

**有问题或建议？**
- 💬 提交 [Issue](https://github.com/lza6/ximagine-2api-pro-python/issues)
- 🔀 发起 [Pull Request](https://github.com/lza6/ximagine-2api-pro-python/pulls)

---

**Made with 💜 by lza6**

*"编程是一门艺术，开源是一种信仰"* 🚀

</div>
]]>
