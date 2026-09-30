# Gemini API 中转站

> 接入最新一代 Gemini，解锁全模态 AI 能力

国内直连中转服务，全面覆盖 **Gemini 3.1 Pro、3.8 Flash、3.5 Flash-Lite** 文本模型，以及 **Nano Banana Pro** 生图、**Veo 3.1** 视频、**Live** 实时语音。**100 万 token 超长上下文**，一次读懂整本书、整个代码库。

🚀 国内直连 · 🧠 1M 超长上下文 · 🖼️ 原生多模态 · 🎬 文生视频 · 🔒 加密稳定 · 💰 官方价 5 折起

- 👉 免费注册领取额度：<https://quanzil.com>

---

## 📦 Gemini 模型系列

从旗舰推理到极速轻量，覆盖文本、生图与视频。

| 模型 | Endpoint / Model ID | 定位 | 上下文 | 价格 |
| --- | --- | --- | --- | --- |
| **Gemini 3.1 Pro** 🏆 | `gemini-3.1-pro-preview` | 最先进的旗舰推理模型 | 1M tokens | 比官方低约 30% |
| **Gemini 3.8 Flash** ⚡ | `gemini-3.8-flash` | 最智能的 Flash，速度智能兼得 | 1M tokens | 比官方低约 40% |
| **Gemini 3.5 Flash-Lite** 🪶 | `gemini-3.5-flash-lite` | 最快最省，高频轻量任务 | 多模态 | 比官方低约 50% |
| **Nano Banana Pro** 🍌 | `gemini-3-pro-image` | 4K 影棚级原生生图引擎 | 按张计费 | 超值 |

### Gemini 3.1 Pro（旗舰推理）

最先进的思考型模型，具备顶级推理、复杂问题求解与 vibe coding 能力，适合最具挑战的任务。

- 100 万 token 超长上下文
- 深度思考 + 多模态理解
- 强大的 Agent 与代码能力
- 复杂文档与长视频分析

### Gemini 3.8 Flash（最强 Flash）

最智能的 Flash 模型，为长程软件工程、自主 Agent 与复杂企业工作流打造，速度与智能兼得。

- 100 万 token 上下文
- 快速响应 + 可调思考预算
- 原生工具调用
- 高吞吐、低延迟

### Gemini 3.5 Flash-Lite（极速轻量）

最快、最具成本效益的模型，为高频、高并发的轻量任务而生，性价比之王。

- 超低延迟响应
- 成本最优，适合规模化
- 多模态输入支持
- 文本摘要与分类

### Nano Banana Pro（原生生图）

带推理内核的专业级设计引擎，可生成 4K 影棚级画质、复杂排版与精准文字渲染的图像。

- 原生图像生成与编辑
- 4K 高清 + 精准文字
- 复杂布局与上下文理解
- 另有 Nano Banana 2 高速版（`gemini-3.1-flash-image`）

> 同时支持 **Veo 3.1** 电影级文生视频、**Gemini 3.8 Live** 实时语音对话、**Gemini 3.5 Transcribe** 语音转写与 **Gemini Embedding 2** 多模态向量。

---

## 🧬 原生全模态能力

一个 API，同时理解与生成文本、图像、音频和视频。

| | 能力 | 说明 |
| --- | --- | --- |
| 📝 | **文本与代码** | 顶级的推理、写作与代码生成，支持结构化输出与函数调用，驱动复杂业务逻辑。 |
| 🖼️ | **图像理解与生成** | 看懂图表、截图、手写稿，并可通过 Nano Banana Pro 生成与编辑 4K 高清图像。 |
| 🎬 | **视频理解与创作** | 解析长视频并总结要点，Veo 3.1 更可生成带原生音效的电影级短片。 |
| 🔊 | **语音与音频** | Live 实时语音对话、130+ 语言高保真 TTS，以及带说话人分离的语音转写。 |
| 🧩 | **Agent 与工具** | 内置 Google 搜索、代码执行、URL 上下文、Computer Use 等工具，构建自主智能体。 |
| 📚 | **百万级长上下文** | 1M token 一次装下整本书、超长代码库或数小时会议记录，配合上下文缓存更省钱。 |

---

## ✨ 为什么选择我们的中转服务

专为中国开发者打造的 Gemini API 接入方案。

| | 优势 | 说明 |
| --- | --- | --- |
| 🌐 | **国内直连访问** | 无需科学上网，直接调用 Gemini API，多线路优化延迟低至 30ms，稳定可靠。 |
| ⚡ | **智能负载均衡** | 多区域节点智能调度与故障自动切换，高并发下依旧保持超快响应。 |
| 🔒 | **企业级安全** | 全链路端到端加密传输，绝不存储任何请求与对话数据，隐私安全有保障。 |
| 💰 | **透明超值定价** | 相比官方节省 30%-50% 成本，支持人民币付款，按量计费更灵活。 |
| 🛠️ | **双协议兼容** | 同时兼容官方 Gemini SDK 与 OpenAI 兼容接口，改一行 `base_url` 即可迁移。 |
| 📞 | **7×24 中文支持** | 专业工程团队全天候在线，快速响应并解决你的一切集成问题。 |

---

## 🚀 快速开始

几分钟内将最新 Gemini 模型集成到你的应用。

### Python

```python
# 安装依赖: pip install google-genai
from google import genai

# 仅需将 base_url 指向中转站
client = genai.Client(
    api_key="your_api_key",
    http_options={"base_url": "https://quanzil.com"}
)

response = client.models.generate_content(
    model="gemini-3.1-pro-preview",
    contents="请帮我写一个 Python 函数来计算斐波那契数列"
)
print(response.text)
```

### Node.js

```javascript
// 安装依赖: npm install @google/genai
import { GoogleGenAI } from "@google/genai";

const ai = new GoogleGenAI({
  apiKey: "your_api_key",
  httpOptions: { baseUrl: "https://quanzil.com" }
});

const res = await ai.models.generateContent({
  model: "gemini-3.8-flash",
  contents: "用一句话介绍一下量子计算"
});
console.log(res.text);
```

### cURL

```bash
# 通过中转站直接调用
curl "https://quanzil.com/v1beta/models/gemini-3.8-flash:generateContent" \
  -H "x-goog-api-key: your_api_key" \
  -H "Content-Type: application/json" \
  -d '{
    "contents": [{ "parts": [{ "text": "你好，Gemini！" }] }]
  }'
```

### 📊 服务指标

| 指标 | 数值 |
| --- | --- |
| 平均响应延迟 | **30ms** |
| 服务可用性 | **99.9%** |
| 最大上下文 | **1M** |
| 技术支持 | **24/7 中文** |

---

## 🔗 准备好接入最新 Gemini 了吗？

访问 <https://quanzil.com> 免费注册并获取你的 API 密钥。

---

<sub>专业的 Gemini API 中转服务 · 让全模态 AI 开发更简单 · 官网：[quanzil.com](https://quanzil.com) · 最后更新：2026-09-30</sub>
