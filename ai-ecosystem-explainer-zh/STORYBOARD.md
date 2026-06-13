# 中文分镜

**格式：** 1920x1080  
**语言：** 简体中文  
**总时长：** 约 4 分 40 秒  
**风格：** 深色科技信息图、关系图动画、卡片式高级解释  
**核心母题：** 工具 / 模型 / 厂商 三层关系反复出现

## 节奏

1. **Beat 1 / 0.00 - 28.00s**
   主题：为什么 AI 名字总让人混淆  
   画面：一团漂浮名词从混乱飞入，随后自动归位到“工具 / 模型 / 厂商”三列。

2. **Beat 2 / 28.00 - 72.00s**
   主题：先建立认知，三层不是一回事  
   画面：顶部工具层、中部模型层、底部公司层，连接线逐步点亮，右侧出现“三个问题”方法论。

3. **Beat 3 / 72.00 - 126.00s**
   主题：海外三大体系  
   画面：OpenAI、Anthropic、Google 三列系统舱，依次聚焦公司、模型、入口和代表人物。

4. **Beat 4 / 126.00 - 181.00s**
   主题：国内三大体系  
   画面：Kimi / Moonshot、DeepSeek、GLM / Z.ai 三列系统舱，突出命名差异与常见入口。

5. **Beat 5 / 181.00 - 250.00s**
   主题：一张总表看懂对应关系  
   画面：横向矩阵信息墙逐行高亮，右侧同步出现“先问三个问题”的判断框架。

6. **Beat 6 / 250.00 - 280.00s**
   主题：结尾总结与关注引导  
   画面：三张问题卡放大停留，背景节点收束，最后收成标题与联系方式。

## 视觉重点

- 核心内容尽量保持在中间 1200px 区域，方便未来裁切为竖版。
- 每个体系不画真实 Logo，用首字母、文字卡、色带和抽象图标代替。
- 背景始终带有缓慢流动的网格、光晕、扫描条或幽灵大字，保证画面不空。

## 关键画面说明

### Beat 1

- 混乱名词：Codex、Claude Code、Gemini、Kimi、DeepSeek、GLM、GPT、Claude、OpenAI、Anthropic、Google、Moonshot AI、智谱 AI
- 第 1 个认知动作：从“名字混乱”到“分类出现”

### Beat 2

- 顶层：ChatGPT、Codex、Claude Code、Gemini AI Studio、Kimi、DeepSeek、GLM / Z.ai
- 中层：GPT-5.5、Claude Opus 4.8、Gemini 3.5 Flash / Pro、Kimi K2.6 / K2.7 Code、DeepSeek-V4-Pro / V4-Flash、GLM-5.1
- 底层：OpenAI、Anthropic、Google、Moonshot AI、DeepSeek、Z.ai / 智谱 AI
- 第 2 个认知动作：从“分类”到“映射关系”

### Beat 3

- OpenAI：ChatGPT / Codex ← GPT-5.5 ← OpenAI
- Anthropic：Claude / Claude Code ← Claude Opus 4.8 ← Anthropic
- Google：Gemini App / AI Studio / API ← Gemini 3.5 Flash / Pro ← Google

### Beat 4

- Kimi：客户端 / 网页版 / API ← Kimi K2.6 / K2.7 Code ← Moonshot AI
- DeepSeek：网页版 / App / API ← DeepSeek-V4-Pro / V4-Flash ← DeepSeek
- GLM：Z.ai / 插件 / API / AutoGLM ← GLM-5.1 ← 智谱 AI / Z.ai

### Beat 5

- 以 6 行矩阵统一呈现体系、厂商、模型、入口、代表人物
- 右侧固定方法论卡：先问“我在哪里用”“背后什么模型”“哪家公司做的”

### Beat 6

- 三张大问题卡：
  - 它是工具、模型，还是公司？
  - 它背后调用什么模型？
  - 这个模型是哪家公司做的？
- 结尾标题：关注文浩 AI
- 联系方式：`wenhaofree`

## 工程结构

```text
ai-ecosystem-explainer-zh/
├── index.html
├── DESIGN.md
├── STORYBOARD.md
├── SCRIPT.md
├── narration.txt
└── .hyperframes/
    └── expanded-prompt.md
```
