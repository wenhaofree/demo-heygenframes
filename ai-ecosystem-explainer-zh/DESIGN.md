# Design System

## Overview

这条视频采用深色科技信息图方向。核心体验不是“炫酷粒子”，而是“复杂关系被迅速理清”。画面要像高级数据舱、策略看板和模型关系图的结合体：结构清晰，信息分层，节奏干净，局部用冷色光晕和扫描线增加科技感。

## Colors

- **Canvas**: `#08111F` - 全片统一深海军蓝背景。
- **Primary Surface**: `#0F1D32` - 主信息面板、场景容器底色。
- **Secondary Surface**: `#112B46` - 次级卡片、表格单元、说明模块。
- **Quiet Border**: `#28507E` - 结构边框、分割线、连接节点描边。
- **Primary Content**: `#F4F7FB` - 主标题、高亮信息、关键标签。
- **Secondary Content**: `#B8C7DA` - 说明文案、辅助描述、表格次要信息。
- **Electric Blue**: `#49B6FF` - 主动线、连接线、扫描和高亮。
- **Signal Aqua**: `#37E8FF` - 次级科技光效、数据波纹。
- **Core Violet**: `#8878FF` - 模型层核心节点、渐变能量中心。
- **OpenAI Green**: `#56F0A9` - OpenAI 体系强调色。
- **Anthropic Amber**: `#FFB56A` - Anthropic 体系强调色。
- **Google Blue**: `#669CFF` - Google 主强调色。
- **Google Red**: `#FF6B6B` - Google 点缀色。
- **Google Yellow**: `#FFD166` - Google 点缀色。
- **Google Green**: `#7AE582` - Google 点缀色。
- **Moonshot Purple**: `#B48DFF` - Kimi / Moonshot 体系强调色。
- **DeepSeek Silver**: `#C9D6E7` - DeepSeek 体系高亮边框和银色节点。
- **DeepSeek Blue**: `#63C7FF` - DeepSeek 主强调色。
- **GLM Indigo**: `#7C9CFF` - GLM / Z.ai 主强调色。
- **GLM Glow**: `#9EE7FF` - GLM 光效和注释强调。

## Typography

- **Headline Display**: `Bricolage Grotesque`, 中文回退 `PingFang SC`, `Hiragino Sans GB`, `Microsoft YaHei`, `sans-serif`
- **Body / UI Sans**: `PingFang SC`, `Hiragino Sans GB`, `Microsoft YaHei`, `sans-serif`
- **Technical Mono**: `IBM Plex Mono`, `SFMono-Regular`, `Menlo`, `monospace`
- **Hero Scale**: 88px - 124px，用于章节主标题与结尾问题。
- **Section Scale**: 54px - 76px，用于场景标题和大卡片标题。
- **Card Scale**: 22px - 34px，用于卡片标签和说明。
- **Micro Label Scale**: 18px - 22px，用于章节编号、类别标签、连接元信息。

## Layout Rules

- 安全内容区集中在画面中轴偏内侧，保证后续裁成 `9:16` 时核心信息仍可读。
- 每屏只讲一个核心认知，不堆积大段文字。
- “工具 / 模型 / 厂商”三层关系必须反复出现，作为全片最稳定视觉母题。
- 表格页字号必须明显大于常规网页表格，保证手机端可读。
- 所有人物只用抽象剪影卡片或姓名标签，不用真实人脸素材。

## Motion

- 主节奏：平稳建立认知，关键节点加速聚焦，再回到清晰总结。
- 主转场：`blur crossfade`，中等强度，保持信息延续感。
- 章节切换时允许加入轻微 `zoom through` 感，但不做重度眩晕运动。
- 背景始终保留低频呼吸光晕、扫描线或慢速漂移网格，避免纯静态。

## Components

- **Word Cloud Chips**: 漂浮名词卡片，进入后自动归类。
- **Relationship Rail**: 工具 → 模型 → 厂商 三层连接轨道。
- **System Lanes**: 单列厂商体系卡，含公司、模型、入口、人物。
- **Insight Panels**: 右侧结论卡或“先问三个问题”卡。
- **Matrix Board**: 汇总表格信息墙，逐行扫描高亮。
- **Question Cards**: 结尾三个方法论问题卡。

## Do's and Don'ts

### Do's

- 用明确结构、节点、连线和扫描节奏体现“信息被整理”的过程。
- 用公司专属色区分体系，但整体画面仍受全片深蓝基底统一。
- 用局部高亮而不是整屏大面积霓虹，保持高级感。
- 让重要信息先出现，辅助解释后出现，层次非常明确。

### Don'ts

- 不要用真实商标 Logo 或高度拟真的人物肖像。
- 不要做紫色赛博朋克堆料，紫色只作为模型层能量色出现。
- 不要做过满的弹幕式排版，一屏控制在 3 到 5 个重点关键词。
- 不要用默认网页字体、默认按钮、默认卡片网格感。
