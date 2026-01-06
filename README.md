# 🎬 Ximagine-2API Pro Python

<div align="center">
<img src="https://img.shields.io/badge/version-2.2.0-blue?style=for-the-badge&logo=python&logoColor=white" alt="Version">
<img src="https://img.shields.io/badge/license-Apache%202.0-green?style=for-the-badge" alt="License">
<img src="https://img.shields.io/badge/python-3.8+-yellow?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/platform-Windows-lightgray?style=for-the-badge&logo=windows&logoColor=white" alt="Platform">

**✨ 一款开箱即用的 AI 视频生成桌面应用 ✨**

*基于 Ximagine API 的本地化代理服务，提供赛博朋克风格 UI 和一键启动体验*

[🚀 快速开始](#-快速开始) • [📖 功能介绍](#-功能介绍) • [🔧 技术原理](#-技术原理详解) • [📊 架构设计](#-系统架构设计)

</div>

## 📣 项目简介

🎉 **你好，开发者/用户！** 欢迎来到这个充满科技感的 AI 视频生成世界！

这个项目可以让你通过简单的操作，将文字描述转化为精彩的 AI 视频：

```
输入文字描述 → 点击生成按钮 → 🎥 获得 AI 生成的视频！
```

**示例：**
- **输入：** `一只可爱的柯基在草地上奔跑`
- **输出：** 一段 5 秒左右的高清视频！

**核心价值：**
- 🎯 **极简体验**：双击运行，无需复杂配置
- 🖥️ **桌面应用**：独立窗口，不依赖浏览器
- 🔐 **隐私安全**：本地运行，数据不留痕
- 🎨 **颜值在线**：赛博朋克 UI，四款炫酷主题

## 🎯 应用场景

| 场景 | 描述 | 适用人群 |
|------|------|----------|
| 🎬 短视频创作 | 快速生成创意视频素材 | 短视频博主、内容创作者 |
| 📱 社交媒体 | 制作吸引眼球的视频内容 | 新媒体运营、营销人员 |
| 🎮 游戏/动画 | 快速产出概念演示视频 | 游戏开发者、动画师 |
| 📚 教学演示 | 生成教学辅助视频素材 | 教师、培训师 |
| 🧪 技术研究 | 研究 AI 视频生成技术 | 开发者、研究人员 |
| 🎁 个人娱乐 | 将创意想法可视化 | 所有创意爱好者 |

## ✨ 核心功能

### 🎨 视频生成模式

| 模式 | 模型 ID | 风格描述 | 效果评级 |
|------|---------|----------|----------|
| 📽️ 标准现实 | `grok-video-normal` | 真实世界风格视频生成 | ⭐⭐⭐⭐⭐ |
| 🎭 趣味卡通 | `grok-video-fun` | 卡通动画风格 | ⭐⭐⭐⭐ |
| 🔥 激情模式 | `grok-video-spicy` | 更具表现力和动感的风格 | ⭐⭐⭐⭐ |
| 🖼️ 图生视频 | `grok-video-image` | 基于上传图片生成视频 | ⭐⭐⭐⭐⭐ |
| 🎨 文生图 | `grok-image` | 文字描述生成静态图片 | ⭐⭐⭐⭐ |

### 📐 支持画面比例

- **1:1** - 方形（适合社交媒体封面/头像）
- **16:9** - 横屏（适合 YouTube、B站等平台）
- **9:16** - 竖屏（适合抖音、小红书等平台）

### 🎨 主题系统

1. **💜 Cyberpunk** - 经典赛博朋克风格（霓虹蓝+霓虹粉）
2. **💚 Matrix** - 黑客帝国风格（经典绿色终端）
3. **🌟 Golden** - 奢华金色主题（尊贵典雅）
4. **🤍 Clean** - 清爽白色模式（简洁护眼）

## 🚀 快速开始

> 🎁 **无需 Python 经验！** 脚本自动完成环境配置！

### 方法一：一键启动（推荐 ⭐⭐⭐⭐⭐）

```bash
# 1. 下载项目
git clone https://github.com/lza6/ximagine-2api-pro-python.git

# 2. 进入项目目录
cd ximagine-2api-pro-python

# 3. 双击运行启动脚本
run.bat
```

启动器自动完成以下步骤：
1. ✅ 检测系统 Python 环境
2. ✅ 自动下载嵌入式 Python（如需要）
3. ✅ 安装所有依赖库
4. ✅ 启动应用程序

### 方法二：手动安装

如已有 Python 环境，可手动安装：

```bash
# 1. 克隆项目
git clone https://github.com/lza6/ximagine-2api-pro-python.git
cd ximagine-2api-pro-python

# 2. 创建虚拟环境（推荐）
python -m venv venv
venv\Scripts\activate  # Windows
# 或 source venv/bin/activate  # Mac/Linux

# 3. 安装依赖
pip install -r requirements.txt

# 4. 启动程序
python main.py
```

## 🎮 使用教程

### Step 1️⃣ 启动应用程序
双击 `run.bat` 文件，等待应用窗口打开

### Step 2️⃣ 界面概览

```
┌─────────────────────────────────────────────────────────────┐
│  🖥️ Ximagine-2API Pro Python v2.2.0                         │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  ┌─────────────────┐        ┌─────────────────────────┐    │
│  │                 │        │                         │    │
│  │   🎛️ 控制面板   │        │      🖼️ 作品展示区       │    │
│  │                 │        │                         │    │
│  │  • 🔑 API信息    │        │  📋 生成任务队列        │    │
│  │  • 📐 画面比例   │        │  ✅ 已完成视频          │    │
│  │  • 🎨 视频风格   │        │  📜 历史记录            │    │
│  │  • 🖼️ 图片上传   │        │                         │    │
│  │  • 📝 创意描述   │        │                         │    │
│  │  • 🚀 生成按钮   │        │                         │    │
│  └─────────────────┘        └─────────────────────────┘    │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

### Step 3️⃣ 开始创作
1. **输入创意描述** - 在文本框中输入你的想法
   ```
   示例：一位宇航员在火星表面行走，背景是壮观的红色星球
   ```

2. **选择画面比例** - 根据发布平台选择合适的比例
   - 横屏视频：16:9
   - 竖屏视频：9:16
   - 方形内容：1:1

3. **选择视频风格** - 根据内容选择合适的风格
   - 现实场景：标准现实
   - 卡通内容：趣味卡通
   - 动态场景：激情模式

4. **上传参考图片**（可选） - 如需图生视频功能

5. **开始生成** - 点击 🚀 按钮开始生成

### Step 4️⃣ 查看和下载
- ⏱️ **等待时间**：通常 30-120 秒
- 📊 **进度显示**：实时显示生成进度
- 💾 **下载视频**：生成完成后点击下载按钮保存

## 🔌 API 接口文档

本项目提供兼容 OpenAI 格式的 API 接口，支持各种客户端调用。

### 📍 基础信息
- **API 地址：** `http://127.0.0.1:9527`
- **API 密钥：** `1`（默认密钥，可修改）

### 📊 接口列表

| 端点 | 方法 | 功能描述 | 请求格式 |
|------|------|----------|----------|
| `/v1/models` | GET | 获取可用模型列表 | - |
| `/v1/chat/completions` | POST | 创建视频/图片生成任务 | JSON |
| `/v1/upload` | POST | 上传参考图片 | Form-Data |
| `/v1/query/status` | GET | 查询任务状态 | Query Params |
| `/v1/proxy/download` | GET | 代理下载生成的视频 | Query Params |

### 🧪 API 调用示例

#### cURL 示例
```bash
# 1. 获取模型列表
curl http://127.0.0.1:9527/v1/models

# 2. 生成视频（SSE流式）
curl http://127.0.0.1:9527/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer 1" \
  -d '{
    "model": "grok-video-normal",
    "messages": [{
      "role": "user",
      "content": "一只猫在钢琴上弹奏爵士乐"
    }],
    "stream": true
  }'
```

#### Python 示例
```python
import requests
import json

# 创建视频生成任务
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
                "prompt": "未来城市的空中交通场景",
                "aspectRatio": "16:9",
                "clientPollMode": True  # 启用异步轮询模式
            })
        }],
        "stream": True
    },
    stream=True
)

# 处理流式响应
for line in response.iter_lines():
    if line:
        print(json.loads(line.decode().replace("data: ", "")))
```

## 📊 系统架构设计

### 总体架构图

```
┌─────────────────────────────────────────────────────────────────────────┐
│                                                                         │
│                    🖥️ 用户界面层 (User Interface Layer)                    │
│                                                                         │
│     ┌─────────────────────────────────────────────────────────┐       │
│     │                                                         │       │
│     │         🪟 PyWebView 桌面应用程序窗口                    │       │
│     │          ┌─────────────────────────────┐               │       │
│     │          │                             │               │       │
│     │          │    🎨 赛博朋克风格 UI       │               │       │
│     │          │    • HTML5 + CSS3           │               │       │
│     │          │    • Vanilla JavaScript     │               │       │
│     │          │    • 四款主题切换           │               │       │
│     │          │                             │               │       │
│     │          └───────────┬─────────────────┘               │       │
│     │                      │                                  │       │
│     │               HTTP 请求/响应                            │       │
│     └──────────────────────┼──────────────────────────────────┘       │
│                            │                                           │
│                            ▼                                           │
├────────────────────────────┼───────────────────────────────────────────┤
│                                                                        │
│                    🔧 后端服务层 (Backend Service Layer)                │
│                                                                        │
│     ┌─────────────────────────────────────────────────────────┐       │
│     │                                                         │       │
│     │                🐍 Flask Web 服务器                      │       │
│     │                  (端口: 9527)                           │       │
│     │                                                         │       │
│     │  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌──────────┐   │       │
│     │  │  模型列表  │ │ 生成任务  │ │ 图片上传  │ │ 状态查询  │   │       │
│     │  │  /v1/    │ │  /v1/    │ │  /v1/    │ │  /v1/    │   │       │
│     │  │  models  │ │  chat/   │ │  upload  │ │  query/  │   │       │
│     │  │          │ │  comple- │ │          │ │  status  │   │       │
│     │  │          │ │  tions   │ │          │ │          │   │       │
│     │  └─────┬────┘ └────┬─────┘ └────┬─────┘ └────┬─────┘   │       │
│     │        │            │            │            │         │       │
│     │        └────────────┼────────────┼────────────┘         │       │
│     │                     │            │                      │       │
│     │               🔄 SSE流式        🔐 RSA加密              │       │
│     └─────────────────────┼────────────┼──────────────────────┘       │
│                           │            │                               │
│                           ▼            ▼                               │
├───────────────────────────┼────────────┼───────────────────────────────┤
│                           │            │                               │
│                    🌐 网络通信层 (Network Layer)                       │
│                           │            │                               │
│     ┌─────────────────────▼────────────▼─────────────────────┐         │
│     │                                                         │         │
│     │           🔄 HTTP 代理 & 请求转发                        │         │
│     │                                                         │         │
│     │        • 随机用户代理生成                                │         │
│     │        • IP地址伪装                                     │         │
│     │        • 请求头优化                                     │         │
│     │                                                         │         │
│     └──────────────────────────┬──────────────────────────────┘         │
│                                │                                        │
│                                ▼                                        │
├────────────────────────────────┼────────────────────────────────────────┤
│                                │                                        │
│                    ☁️ 上游服务层 (Upstream Service Layer)               │
│                                │                                        │
│     ┌──────────────────────────▼──────────────────────────────┐         │
│     │                                                         │         │
│     │                🌟 Ximagine API 服务                     │         │
│     │            (https://api.ximagine.io)                    │         │
│     │                                                         │         │
│     │  ┌────────────────────────────────────────────┐        │         │
│     │  │                                            │        │         │
│     │  │         🤖 AI 视频/图像生成引擎            │        │         │
│     │  │        • 文生视频                          │        │         │
│     │  │        • 图生视频                          │        │         │
│     │  │        • 文生图                            │        │         │
│     │  │                                            │        │         │
│     │  └────────────────────────────────────────────┘        │         │
│     │                                                         │         │
│     └─────────────────────────────────────────────────────────┘         │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### 核心模块详解

#### 1️⃣ **用户界面模块**
- **技术栈：** PyWebView + HTML5 + CSS3 + Vanilla JS
- **特点：**
  - 原生桌面应用窗口
  - 响应式布局设计
  - 实时进度展示
  - 四款主题切换

#### 2️⃣ **API 网关模块**
- **技术栈：** Flask + Flask-CORS
- **功能：**
  - RESTful API 接口
  - 请求验证和过滤
  - 错误处理和日志
  - 跨域资源共享

#### 3️⃣ **任务管理模块**
- **实现方式：** 异步任务队列 + 轮询机制
- **流程：**
  ```
  用户提交 → 生成任务ID → 后台处理 → 轮询状态 → 返回结果
  ```

#### 4️⃣ **安全通信模块**
- **加密算法：** RSA-OAEP + SHA-256
- **功能：**
  - 请求身份验证
  - 数据传输加密
  - 防重放攻击

#### 5️⃣ **代理转发模块**
- **技术实现：** Requests + 流式传输
- **特点：**
  - 随机指纹生成
  - 请求头伪装
  - 流式文件下载
  - 错误重试机制

## 🔧 技术原理详解

### 核心工作机制

```python
# 简化的核心流程示意
class XimagineEngine:
    def generate_video(self, prompt, config):
        # 1. 生成请求指纹
        identity = self.generate_identity()
        
        # 2. RSA 加密鉴权
        encrypted_auth = self.encrypt_auth_payload()
        
        # 3. 向上游 API 发起请求
        response = self.call_upstream_api(
            prompt=prompt,
            identity=identity,
            auth=encrypted_auth
        )
        
        # 4. 处理 SSE 流式响应
        if config.get('stream', True):
            return self.handle_sse_stream(response)
        else:
            return self.handle_sync_response(response)
```

### 关键技术解析

#### 🔐 **RSA 非对称加密**
```python
from cryptography.hazmat.primitives.asymmetric import padding
from cryptography.hazmat.primitives import hashes

def encrypt_auth_payload(self, payload):
    """使用 RSA-OAEP 算法加密认证数据"""
    encrypted = self.public_key.encrypt(
        payload.encode(),
        padding.OAEP(
            mgf=padding.MGF1(algorithm=hashes.SHA256()),
            algorithm=hashes.SHA256(),
            label=None
        )
    )
    return base64.b64encode(encrypted).decode()
```

**作用：** 确保上传请求的安全性和完整性，防止中间人攻击。

#### 🌊 **SSE 服务器推送**
```python
@app.route('/v1/chat/completions', methods=['POST'])
def chat_completions():
    def generate():
        for chunk in video_generation_stream():
            yield f"data: {json.dumps(chunk)}\n\n"
    
    return Response(
        generate(),
        mimetype='text/event-stream',
        headers={
            'Cache-Control': 'no-cache',
            'X-Accel-Buffering': 'no'
        }
    )
```

**作用：** 实时推送生成进度，提升用户体验。

#### 🎭 **指纹伪装系统**
```python
def generate_identity(self):
    """生成随机浏览器指纹"""
    return {
        'ip': f"{randint(1,255)}.{randint(1,255)}.{randint(1,255)}.{randint(1,255)}",
        'user_agent': random.choice(USER_AGENTS),
        'accept_language': 'zh-CN,zh;q=0.9,en;q=0.8',
        'referer': 'https://www.ximagine.ai/',
        'sec_ch_ua': '"Chromium";v="128", "Not:A-Brand";v="24"'
    }
```

**作用：** 绕过反爬虫机制，模拟真实用户请求。

#### 🔄 **异步轮询机制**
```javascript
// 前端轮询实现
function pollTaskStatus(taskId) {
    const interval = setInterval(async () => {
        const response = await fetch(`/v1/query/status?taskId=${taskId}`);
        const data = await response.json();
        
        if (data.status === 'completed') {
            clearInterval(interval);
            showResult(data.result);
        } else if (data.status === 'failed') {
            clearInterval(interval);
            showError(data.error);
        } else {
            updateProgress(data.progress);
        }
    }, 2000); // 每2秒轮询一次
}
```

**作用：** 实现长时间任务的异步处理，避免请求超时。

## 📁 项目文件结构

```
ximagine-2api-pro-python/
│
├── 📄 main.py                      # 主程序入口（919行代码）
│   ├── 📦 CONFIG                    # 全局配置常量
│   ├── ⚙️ XimagineEngine           # 核心引擎类
│   ├── 🌐 API 路由定义              # 5个核心API端点
│   ├── 🎨 UI 界面代码               # 完整的HTML/CSS/JS
│   └── 🚀 程序启动逻辑
│
├── 📄 requirements.txt             # Python依赖清单
│   ├── flask>=2.3.0               # Web框架
│   ├── flask-cors>=4.0.0          # 跨域支持
│   ├── requests>=2.31.0           # HTTP客户端
│   ├── pywebview>=4.4.0           # 桌面窗口
│   └── cryptography>=41.0.0       # 加密算法
│
├── 📄 run.bat                      # 智能启动脚本（260行）
│   ├── 🔍 环境检测模块
│   ├── 📥 自动下载模块
│   ├── ⚙️ 依赖安装模块
│   ├── ✅ 状态标记模块
│   └── 🚀 应用启动模块
│
├── 📄 .env_ready                   # 环境就绪标记文件
├── 📄 ximagine_data.json           # 数据持久化文件
│
├── 📁 venv/                        # Python虚拟环境
├── 📁 python/                      # 嵌入式Python运行时
├── 📁 main.build/                  # Nuitka构建缓存
└── 📁 main.dist/                   # 可执行文件输出
```

## 💎 优势与局限

### ✅ 核心优势

| 特性 | 说明 | 优势评级 |
|------|------|----------|
| 🚀 一键启动 | 无需环境配置，双击即用 | ⭐⭐⭐⭐⭐ |
| 🖥️ 桌面原生 | 独立窗口，性能更佳 | ⭐⭐⭐⭐⭐ |
| 🎨 界面美观 | 赛博朋克风格，主题切换 | ⭐⭐⭐⭐⭐ |
| 🔗 API兼容 | 支持OpenAI标准接口 | ⭐⭐⭐⭐⭐ |
| 🔐 安全加密 | RSA加密传输，数据安全 | ⭐⭐⭐⭐⭐ |
| 📡 实时推送 | SSE流式进度展示 | ⭐⭐⭐⭐ |
| 🌐 代理下载 | 绕过跨域限制 | ⭐⭐⭐⭐ |

### ⚠️ 当前局限

| 局限 | 说明 | 改进计划 |
|------|------|----------|
| 💻 平台限制 | 仅支持Windows系统 | Q3 2024支持macOS/Linux |
| 🌐 网络依赖 | 需要连接Ximagine API | 未来支持本地模型 |
| ⏱️ 生成时长 | 视频生成需30-120秒 | 优化异步处理机制 |
| 💾 数据持久化 | 刷新后数据丢失 | 集成SQLite数据库 |

## 🛣️ 发展路线图

### 🎯 近期计划（2024 Q3）

- [ ] **v2.3.0** - 增加任务队列管理
- [ ] **v2.4.0** - 集成SQLite本地数据库
- [ ] **v2.5.0** - 添加系统托盘支持
- [ ] **v2.6.0** - 支持自定义API配置

### 🚀 中期规划（2024 Q4）

- [ ] **跨平台支持** - macOS和Linux版本
- [ ] **Web版本** - 可部署的Web应用
- [ ] **Docker支持** - 容器化部署
- [ ] **插件系统** - 扩展功能支持

### 🌟 长期愿景（2025）

- [ ] **多后端支持** - 集成Runway、Pika等
- [ ] **视频编辑** - 基础剪辑和拼接
- [ ] **音频集成** - 背景音乐和配音
- [ ] **社区功能** - 作品分享和提示词市场

## 🔧 扩展开发指南

### 添加新模型支持

```python
# 在CONFIG中添加模型定义
MODEL_MAP = {
    "new-video-model": {
        "type": "video",
        "mode": "enhanced",
        "channel": "new_channel",
        "pageId": 999,
        "name": "增强视频模型"
    }
}

# 前端会自动从/v1/models获取
```

### 自定义UI主题

```css
/* 添加新主题变量 */
:root.theme-neon-green {
    --primary-color: #00ff00;
    --secondary-color: #00cc00;
    --accent-color: #33ff33;
    --bg-color: #001100;
    --text-color: #ffffff;
}

/* 在前端添加主题切换选项 */
```

### 开发新API端点

```python
@app.route('/v1/batch/generate', methods=['POST'])
def batch_generate():
    """批量生成接口示例"""
    tasks = request.json.get('tasks', [])
    results = []
    
    for task in tasks:
        task_id = create_generation_task(
            prompt=task['prompt'],
            model=task.get('model', 'grok-video-normal')
        )
        results.append({'task_id': task_id})
    
    return jsonify({
        'success': True,
        'data': results,
        'count': len(results)
    })
```

## 🐛 故障排除

| 问题 | 可能原因 | 解决方案 |
|------|----------|----------|
| 无法启动应用 | Python环境问题 | 使用run.bat自动配置环境 |
| 生成任务失败 | 网络连接问题 | 检查网络连接，重试操作 |
| 下载视频失败 | 跨域限制 | 使用代理下载功能 |
| 界面显示异常 | 缓存问题 | 重启应用或清除缓存 |
| API调用错误 | 请求格式错误 | 检查API文档和示例 |

## 🤝 贡献指南

我们欢迎各种形式的贡献：

### 代码贡献
1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 文档改进
- 修正文档错误
- 补充使用示例
- 翻译文档
- 添加教程

### 问题反馈
- 提交Bug报告
- 提出新功能建议
- 分享使用经验

## 📄 许可证

本项目基于 **Apache License 2.0** 许可证开源。详见 [LICENSE](LICENSE) 文件。

## 🙏 致谢

感谢以下开源项目：

- 🐍 [Python](https://python.org) - 编程语言
- 🔥 [Flask](https://flask.palletsprojects.com) - Web框架
- 🖥️ [PyWebView](https://pywebview.flowrl.com) - 桌面应用封装
- 🔐 [Cryptography](https://cryptography.io) - 加密库
- 🎨 [Font Awesome](https://fontawesome.com) - 图标库

## 🌟 支持项目

如果这个项目对你有帮助：

1. ⭐ **Star 这个仓库** - 让更多人看到
2. 🐛 **报告问题** - 帮助改进项目
3. 💬 **分享经验** - 帮助其他用户
4. ☕ **捐赠支持** - 支持持续开发

---

<div align="center">

## 🎬 让创意可视化，让想象成现实

**如果喜欢这个项目，请给它一个 Star ⭐**

```
代码开源 • 知识共享 • 社区共建
```

**项目维护者：** [lza6](https://github.com/lza6)

*最后更新：2026年1月7日 04:28:24 | 版本：v2.2.0*

</div>
