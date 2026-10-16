<div align="center">

# 👋 Hi, I'm 李莹莹 (Yingying Li)

**AI Agent & RAG Engineer | 27届应届生**

[![trophy](https://img.shields.io/badge/🏆_蓝桥杯-智能体开发_全国一等奖-FFD700?style=for-the-badge)](https://github.com/lyy-0118)
[![trophy](https://img.shields.io/badge/🥇_蓝桥杯-C%2FC%2B%2B_省一等奖-C0C0C0?style=for-the-badge)](https://github.com/lyy-0118)
[![trophy](https://img.shields.io/badge/🏅_西门子杯-全国初赛一等奖-CD7F32?style=for-the-badge)](https://github.com/lyy-0118)

[![Email](https://img.shields.io/badge/📧-lyy01188@163.com-blue?style=flat-square&logo=gmail)](mailto:lyy01188@163.com)
[![Phone](https://img.shields.io/badge/📱-19725518835-green?style=flat-square)](tel:19725518835)
[![University](https://img.shields.io/badge/🎓-湖北科技学院_人工智能-red?style=flat-square)](https://github.com/lyy-0118)

</div>

---

## 🚀 关于我

> 求职方向：**AI Agent / AI 应用开发工程师**

本科就读于**湖北科技学院人工智能专业（2027届）**，主导参与校企合作 AI 项目，完整交付过包含 **RAG、LLM微调、RTC语音、MCP多Agent** 的企业级 AI 生态矩阵。持有软件著作权 3 项，**蓝桥杯智能体开发全国一等奖**获得者。

---

## 🛠️ 技术栈

<div align="center">

**AI / LLM**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**RAG & Vector DB**

![PostgreSQL](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**工程 & 部署**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

</div>

---

## 💡 核心能力

| 领域 | 技术点 |
|------|--------|
| 🔍 **RAG 全链路** | 自定义切片 · HNSW_HYBRID · Int8量化 · Rerank · MMR · dense_weight调优 |
| 🤖 **Agent 编排** | LangGraph SubGraph · PostgreSQL Checkpointer · LangSmith · MCP Server |
| 🧠 **LLM 微调** | QLoRA/LoRA · LLaMA-Factory · SFT→DPO · 火山引擎方舟 |
| ⚡ **LLM 推理优化** | Prefix Caching · KV Cache · TTFT优化 · 多模型动态路由 |
| 🎙️ **RTC 实时语音** | ASR/TTS · 声音复刻 · FEC前向纠错 · 自适应Jitter Buffer |
| 🔧 **后端工程** | FastAPI · asyncio · Pydantic · SSE流式输出 · 容器化部署 |

---

## 🏗️ 核心项目 —— 企业级 AI 生态矩阵

> 与**武汉精臣智慧标识科技**（国内标签打印机头部企业）深度合作，主导研发 5 大 AI 模块

<table>
<tr>
<td width="50%" valign="top">

### 📊 数据中台 & 模型微调
**ETL 全链路 + SFT→DPO 两阶段微调**
- 多源数据（微信/WhatsApp/独立站）抽取清洗
- ShareGPT/OpenAI JSONL 多格式导出
- QLoRA 本地验证 → 云端 LoRA 生产训练
- 微调"金牌销冠"风格客服模型，形成 RAG+微调闭环

</td>
<td width="50%" valign="top">

### 🎙️ 多模态实时语音客服 Agent
**RTC 架构 + 多模态 RAG**
- Prefix Caching 命中率优化，TTFT 显著降低
- Int8量化 + Metadata过滤，检索速度提升 **4x**
- 弱网（50%丢包）环境语音无感知恢复
- 文字+图片+视频混排回复

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔗 MCP 多 Agent 共享基座
**服务化重构 + 多租户隔离**
- LLM网关 / RAG / 记忆抽离为独立 MCP Server
- FastAPI 四层中间件（认证→日志→配额→路由）
- pgvector 1024维 + HNSW，召回相似度提升至 **0.71**
- AI 自动出题 + 五维自动打分考核系统

</td>
<td width="50%" valign="top">

### ✂️ 直播切片 Agent
**端到端自动化 Pipeline**
- FFmpeg.wasm 浏览器端提音，2.5GB→30MB（**↓99%**）
- Groq Whisper ASR + Map-Reduce 处理 6小时长视频
- SSE 实时状态推送，构建可观测 Pipeline
- 高光片段反哺 RAG 知识库与 MCP 素材中心

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 📱 社媒内容生成 & 自动化运营 Agent
**LangGraph 多阶段工作流 + 异步并行优化**
- PostgreSQL Checkpointer 持久化，支持任意节点回滚
- asyncio.gather + 信号量控制 + 指数退避，生成耗时缩短 **70%**
- 轻量/旗舰模型动态路由，降低推理成本 **40%**
- 适配小红书 / Instagram / Twitter 多平台

</td>
</tr>
</table>

---

## 🏆 荣誉奖项

| 奖项 | 级别 |
|------|------|
| 🥇 第十七届蓝桥杯 · **智能体开发** | **全国一等奖** |
| 🥇 第十七届蓝桥杯 · **C/C++ 程序设计** | **省一等奖** |
| 🥇 第二十届西门子杯 | **全国初赛一等奖** |
| 🥉 中国机器人及人工智能大赛 | 省三等奖 |
| 📜 情绪检测相关**软件著作权** | **3 项** |

---

## 📈 GitHub 统计

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=lyy-0118&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lyy-0118&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

**📧 lyy01188@163.com · 📱 19725518835**

*湖北科技学院 · 人工智能本科 · 2027届应届生*

![Visitor Count](https://komarev.com/ghpvc/?username=lyy-0118&color=blueviolet&style=flat-square)

</div>
