<div align="center">

<img src="https://img.shields.io/badge/ResuMatch-AI%20简历定制-0066cc?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTYgMTYiIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIyIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxwb2x5bGluZSBwb2ludHM9IjIsMTMgNiw4IDksMTEgMTMsNSIvPjxjaXJjbGUgY3g9IjEzIiBjeT0iNSIgcj0iMS44IiBmaWxsPSIjZmZmIiBzdHJva2U9Im5vbmUiLz48L3N2Zz4=" alt="ResuMatch">

# ResuMatch · AI 简历定制工具

**一个页面，零依赖，点开即用的 AI 简历定制神器**

基于大语言模型，将你的原始履历与目标岗位 JD 精准匹配，生成高匹配度的定制简历与深度分析报告

[立即开始](https://resumatch.gzl406633204.workers.dev/)

[功能演示](#-核心功能) · [支持模型](#-支持的-ai-模型) · [常见问题](#-常见问题) · [贡献指南](#-贡献)

---

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Single File](https://img.shields.io/badge/架构-单文件%20HTML-brightgreen)](resumatch-universal.html)
[![No Backend](https://img.shields.io/badge/后端-无需服务器-orange)](resumatch-universal.html)
[![Data Privacy](https://img.shields.io/badge/数据-本地调用，不上传-green)](resumatch-universal.html)
[![Stars](https://img.shields.io/github/stars/yourusername/resumatch?style=social)](https://github.com/nathanielguo/resumatch)

</div>

---

## 📌 这是什么

ResuMatch 是一个**帮助求职者将同一份基础简历快速定制为高度匹配不同公司 JD 的版本的工具，便于求职者快速投递对应岗位JD的简历**

**核心逻辑：** 不同公司、不同岗位对同样背景的候选人需求侧重点不同。ResuMatch 通过 AI 深度分析目标 JD，识别核心关键词与能力要求，对你的原始简历进行结构重组、重点突出与专业化表述，同时提供量化匹配评分与面试建议。

> ⚠️ **真实性承诺：** 工具仅对你已有的经历进行重新组织与优化表述，不虚构任何工作经历、数字指标、证书或技能。所有生成内容均有据可查。

---

## ✨ 核心功能

### 🎯 AI 深度简历改写
- 逐段分析工作经历，识别与 JD 的关联点
- 将最相关的职责与成果前置，融入 JD 关键词体系
- 每个要点以行动动词开头，采用 STAR 法则重构表述
- 保留并突出原有量化数据，不编造新数字

### 🧩 AI 智能扩写建议
- 识别 JD 要求但简历未明确体现的软性能力
- 基于现有经历合理推断可能具备的能力，生成「AI 建议」补充要点
- 橙色标注区分 AI 建议内容，候选人确认后采用
- 底部独立展示「扩写建议」卡片，说明推断依据

### 📊 多维度匹配评分
- **综合匹配分**（0–100）：整体契合度
- **五维度评分**：工作经验 / 技能能力 / 行业背景 / 学历背景 / 语言能力
- **关键词命中分析**：蓝色标签 = 已命中，划线标签 = 缺口项
- **匹配亮点摘要**：3 条最契合的优势

### 📋 深度分析报告
- 优化说明：每项改写的调整内容与原因
- 核心优势：候选人相对该岗位的差异化竞争力
- 差距分析：JD 要求 vs 现状 + 应对建议
- 面试准备：针对该公司/岗位的具体可执行建议

### 📄 灵活导出
| 导出方式 | 内容 | 格式 |
|---------|------|------|
| 复制简历正文 | 仅简历内容（可直接粘贴进 Word） | 纯文本 |
| 复制完整报告 | 简历 + 全部分析内容 | 纯文本 |
| 导出 TXT | 完整报告，含公司名+日期文件名 | `.txt` |
| 导出 PDF | 完整结果区（评分+简历+分析报告） | A4 PDF |

---

## 🤖 支持的 AI 模型

| 提供商 | 模型 | 国内直连 | 推荐指数 |
|--------|------|---------|---------|
| **Anthropic** | Claude Opus 4.5 / Sonnet 4 / Haiku 4.5 | ❌ 需代理 | ⭐⭐⭐⭐⭐ |
| **OpenAI** | o3 / GPT-4o / GPT-4o mini / GPT-4 Turbo | ❌ 需代理 | ⭐⭐⭐⭐⭐ |
| **Google** | Gemini 2.5 Pro / 2.0 Flash / 1.5 Pro | ❌ 需代理 | ⭐⭐⭐⭐ |
| **DeepSeek** | DeepSeek-R1（推理） / V3 | ✅ 直连 | ⭐⭐⭐⭐⭐ |
| **阿里云** | Qwen-Max / QwQ-Plus / Qwen-Plus / Turbo | ✅ 直连 | ⭐⭐⭐⭐ |
| **智谱 AI** | GLM-4-Plus / Long / Air / Flash（免费） | ✅ 直连 | ⭐⭐⭐ |

> 💡 **国内用户推荐**：DeepSeek-R1 或 Qwen-Max，无需代理，效果优异，价格极低。追求最高质量可使用 Claude Sonnet 4（需代理）。

---

## 🚀 快速开始

### 方式一：直接下载使用

```bash
# 1. 下载文件
git clone https://github.com/nathanielguo/resumatch.git

# 2. 用浏览器打开（无需安装任何依赖）
open resumatch-universal.html
# 或双击文件在浏览器中打开
```

### 方式二：在线访问（推荐）

[点击访问](https://resumatch.gzl406633204.workers.dev/)

### 使用步骤

```
Step 1 · 配置 API
  └─ 选择模型提供商 → 填写 API 密钥 → 点击「验证连接」确认可用

Step 2 · 输入内容
  └─ 粘贴完整个人履历（越详细效果越好）
  └─ 粘贴目标公司的完整 JD

Step 3 · 生成 & 导出
  └─ 点击「生成定制简历」→ 等待 20–50 秒
  └─ 查看匹配评分、改写后简历、AI 扩写建议、深度分析
  └─ 导出 PDF / TXT 或复制使用
```

---

## ⚙️ 设置说明

### 生成参数

| 参数 | 选项 | 说明 |
|------|------|------|
| **输出语言** | 简体中文 / English / 中英双语 | 简历与报告的输出语言 |
| **简历篇幅** | 精简 / 标准 / 详尽 | 控制每段工作经历的要点数量 |
| **匹配力度** | 保守 / 均衡 / 深度 | 改写时对 JD 语言体系的融入程度 |
| **行业领域** | 9 大行业可选 | AI 采用对应行业的专业术语体系 |

### 支持的行业

通用（不限行业）· 互联网/科技 · 金融/投资 · 医疗/健康 · 快消/零售 · 制造/工业 · 咨询/管理 · 教育/培训 · 政府/事业单位

---

## 🔑 如何获取 API 密钥

| 平台 | 获取地址 | 说明 |
|------|---------|------|
| Claude | [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys) | 综合能力最强 |
| OpenAI | [platform.openai.com/api-keys](https://platform.openai.com/api-keys) | GPT 系列 |
| Gemini | [aistudio.google.com/apikey](https://aistudio.google.com/apikey) | 有免费额度 |
| DeepSeek | [platform.deepseek.com/api_keys](https://platform.deepseek.com/api_keys) | 国内直连，性价比极高 |
| 通义千问 | [dashscope.console.aliyun.com](https://dashscope.console.aliyun.com/apiKey) | 国内直连，阿里云 |
| 智谱 GLM | [open.bigmodel.cn](https://open.bigmodel.cn/usercenter/apikeys) | 国内直连，有免费额度 |

> 🔐 **隐私保障**：API 密钥仅存储在你的浏览器，所有请求直接从你的浏览器发送至 AI 服务商，不经过任何中间服务器，Resumatch 不收集任何用户数据。

---

## 🏗️ 技术架构

```
resumatch-universal.html          ← 唯一的文件，即是全部
│
├── UI Layer                      纯 HTML + CSS（无框架）
│   ├── 三步骤导航流程
│   ├── API 配置面板
│   ├── 双栏输入区
│   └── 结果展示区（评分 + 简历 + 分析）
│
├── API Layer                     浏览器直接调用，无后端
│   ├── callClaude()              Anthropic Messages API
│   ├── compat(url)               OpenAI 兼容接口（DeepSeek/Qwen/GLM/OpenAI）
│   └── callGemini()              Google Generative Language API
│
├── Prompt Engine                 结构化双阶段提示词
│   ├── 改写规则（零虚构 + 真正改写 + 智能扩写）
│   ├── 行业适配语言体系
│   └── 结构化 JSON 输出格式
│
└── Export Layer
    ├── buildResumeText()         纯简历文本
    ├── buildFullText()           完整报告文本
    ├── exportTxt()               下载 .txt
    └── exportPdf()               @media print → A4 PDF
```

**技术选型原则：**
- **零依赖**：无 Node.js、无 npm、无构建工具，双击即用
- **单文件**：HTML + CSS + JS 全部内联，便于分享与部署
- **Blob 请求体**：所有 API 请求使用 `new Blob([JSON.stringify(...)])` 编码，规避浏览器 ISO-8859-1 字符集限制，确保中文 Prompt 正常传输

---

## 📸 界面预览

```
┌─────────────────────────────────────────────────────┐
│  ★ ResuMatch · AI 简历定制        免费·开源·数据不上传 │
├──────────┬──────────────┬──────────────────────────-─┤
│  配置 API │  输入履历&JD  │     生成 & 导出              │
├─────────────────────────────────────────────────────┤
│                                                     │
│  ┌── 选择模型 ────────────────────────────────────┐ │
│  │  Claude · GPT · Gemini · DeepSeek · 千问 · GLM│ │
│  │  API Key: ████████████  模型: claude-sonnet-4  │ │
│  └──────────────────────────────────────────────-─┘ │
│                                                     │
│  ┌── 您的履历 ──┐  ┌── 目标 JD ──────────────────┐ │
│  │              │  │                             │ │
│  │  粘贴原始    │  │  粘贴目标岗位描述            │ │
│  │  个人简历    │  │  Job Description            │ │
│  │              │  │                             │ │
│  └──────────────┘  └─────────────────────────────┘ │
│                                                     │
│            ★ 生成定制简历                            │
│                                                     │
├─────────────────────────────────────────────────────┤
│  定制简历已生成 — XX公司  [复制] [复制报告] [TXT] [PDF]│
├─────────────────────────────────────────────────────┤
│  ┌──────┐  工作经验 ████████░░  75       匹配亮点    │
│  │  82  │  技能能力 █████████░  80    · 7年行业经验  │
│  │ /100 │  行业背景 ███████░░░  70    · 量化成果显著 │
│  │ 良好 │  学历背景 █████████░  85    · 跨部门协作   │
│  └──────┘  语言能力 ██████░░░░  60                  │
├─────────────────────────────────────────────────────┤
│  关键词匹配  ✓ 20项命中  3项待补强                    │
│  [区域管理][KOL营销][跨部门协作]... [免疫领域][直接下属]│
├─────────────────────────────────────────────────────┤
│  改写策略：本次将市场活动经历前置，融入生态圈建设语言... │
│                                                     │
│  【职业概述】                                         │
│  【工作经历】  XX公司  区域市场经理  2021–2025         │
│    · 主导 40+ 场全国级学术活动，覆盖 XX 家医院...      │
│    · [AI建议] 推动跨职能协作机制建立...               │
│                                                     │
│  ┌──────────┐ ┌──────────┐ ┌──────────┐ ┌────────┐ │
│  │ 优化说明  │ │ 核心优势  │ │ 差距分析  │ │求职策略│ │
│  └──────────┘ └──────────┘ └──────────┘ └────────┘ │
│  面试准备建议：1. 准备生态圈案例... 2. 研究公司管线...  │
└─────────────────────────────────────────────────────┘
```

---

## 🙋 常见问题

**Q：API 密钥安全吗？会被收集吗？**  
A：完全安全。密钥仅存在你的浏览器内存中，所有请求直接发往 AI 服务商，ResuMatch 没有后端，不收集任何数据。关闭页面后密钥自动清除。

**Q：国内用户推荐用哪个模型？**  
A：优先使用 **DeepSeek-R1** 或 **通义千问 Max**，国内可直连，无需代理，效果优异。如有代理可使用 Claude Sonnet 4，综合质量最高。

**Q：生成失败提示"Failed to fetch"怎么办？**  
A：访问 Claude / OpenAI / Gemini 需要代理。国内可直连的选项：DeepSeek、通义千问、智谱 GLM，切换后重试即可。

**Q：简历内容会被 AI 公司保留吗？**  
A：取决于你使用的 AI 服务商的隐私政策。建议：① 敏感信息（如真实手机号）可先替换为占位符后生成；② 使用企业版 API（如 Claude Pro API）通常默认不训练用户数据。

**Q：AI 建议的内容可以直接用吗？**  
A：AI 建议标注为「AI建议」的条目是基于你现有经历的合理推断，**务必逐条确认是否符合实际情况**，准确的直接使用，不准确的删除。工具的真实性承诺是针对原有经历改写部分，AI 建议属于辅助参考。

**Q：可以用于英文简历吗？**  
A：支持。在设置中将「输出语言」切换为 English，即可生成全英文简历与分析报告，适合投递外资企业或海外岗位。

**Q：生成时间很长，正常吗？**  
A：正常。Prompt 包含完整履历与 JD 分析，响应通常需要 20–50 秒。使用推理模型（如 DeepSeek-R1、o3）可能更长，但质量更高。

---

## 📝 使用建议

为获得最佳生成效果，请注意：

**履历填写**
- 尽量提供完整内容：公司名、职位、起止时间、具体职责、量化成果
- 原有的数字指标（覆盖医院数、市场份额、活动规模等）一定要写进去，AI 会帮你突出
- 包含教育、技能、证书、语言等所有维度信息

**JD 处理**
- 粘贴完整原始 JD，包括职责、要求、优先条件等全部内容
- JD 越完整，关键词匹配越精准
- 不同公司同类岗位的 JD 可以分别生成，针对性更强

**参数选择**
- 第一次投递某公司：用「均衡」匹配力度 + 「标准」篇幅
- 强竞争岗位：用「深度」匹配 + 「详尽」篇幅
- 筛选简历用途：用「精简」篇幅，突出重点

---

## 🗺️ 开发路线

- [x] 多模型提供商支持（Claude / GPT / Gemini / DeepSeek / Qwen / GLM）
- [x] 结构化工作经历改写（逐段、逐条）
- [x] AI 智能扩写建议（标注区分）
- [x] 五维度匹配评分系统
- [x] 完整分析报告（优化说明 / 优势 / 差距 / 面试建议）
- [x] PDF 导出（完整报告，A4 排版）
- [x] TXT 导出 + 复制功能
- [x] 行业领域适配（9 大行业）
- [x] 中英双语输出
- [ ] 历史记录（localStorage 存储多次生成结果）
- [ ] 多版本对比（同一履历 vs 不同 JD 的匹配结果对比）
- [ ] 批量模式（一份履历 × N 个 JD，批量生成）
- [ ] Word (.docx) 格式导出
- [ ] 自定义简历模板

欢迎通过 Issue 提交功能建议 →

---

## 🤝 贡献

欢迎任何形式的贡献！

```bash
# Fork 本仓库后
git clone https://github.com/yourusername/resumatch.git
cd resumatch

# 所有代码在单个 HTML 文件中
# 用任何文本编辑器打开即可开始修改
code resumatch-universal.html

# 测试：用浏览器打开修改后的文件
# 无需构建步骤
```

**贡献方向：**
- 🐛 Bug 修复：通过 Issue 描述后提交 PR
- ✨ 功能增强：建议先开 Issue 讨论方案
- 🌐 多语言：欢迎添加其他语言的 UI 版本
- 📝 文档：补充使用案例、截图等
- 🎨 设计：UI 改进建议

---

## 📄 开源协议

本项目基于 [MIT License](LICENSE) 开源。

你可以自由地使用、复制、修改、合并、发布、分发此软件。唯一的要求是在副本中保留版权声明。

---

## 🙏 致谢

感谢以下 AI 服务提供商提供的强大语言模型能力：

[Anthropic](https://anthropic.com) · [OpenAI](https://openai.com) · [Google DeepMind](https://deepmind.google) · [DeepSeek](https://deepseek.com) · [阿里云通义](https://tongyi.aliyun.com) · [智谱 AI](https://zhipuai.cn)

---

<div align="center">

**如果这个工具对你有帮助，欢迎给个 ⭐ Star — 这是对作者最大的鼓励**

Made with ❤️ · 数据不上传 · 完全本地运行

</div>
