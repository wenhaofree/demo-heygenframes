# 中文分镜

**格式：** 1920x1080  
**音频：** 中文旁白 + 轻电子底乐  
**语气：** 面向创业者，直接、可信、推动购买  
**总时长：** 29.8s

## 节奏

1. **Beat 1 / 0.00-6.40s**
   主题：几小时上线，不是几个月  
   画面：中文首页 Hero 截图做玻璃背景，主标题三行推进，右侧产品主视觉发光。  
   旁白：几小时，不是几个月。ShipSaaS 把认证、支付、国际化和部署全部接好。

2. **Beat 2 / 6.40-12.28s**
   主题：跳过基础搭建  
   画面：四张功能卡片和 `200+` 小时计数器，突出认证、支付、国际化、部署。  
   旁白：跳过两百多个小时的基础搭建。认证、订阅、邮件和多语言，开箱即用。

3. **Beat 3 / 12.28-17.34s**
   主题：现代技术栈与全球部署  
   画面：中文流程截图打底，技术栈跑马灯、终端窗口、全球部署提示同步出现。  
   旁白：现代技术栈已经就绪，性能强，扩展稳，全球部署也很快。

4. **Beat 4 / 17.34-24.20s**
   主题：真实口碑  
   画面：三张中文评价卡片依次进场，背景大号 `1,000+`，最后落到“更少折腾，更快上线”。  
   旁白：已经有一千多位开发者在用 ShipSaaS。两小时跑通首版，不再被样板代码拖慢。

5. **Beat 5 / 24.20-29.80s**
   主题：价格与行动号召  
   画面：中文定价区截图做氛围层，左侧 `$99` 大价签，右侧能力清单，最后收进品牌口号。  
   旁白：现在，终身版只要九十九美元。一次买断，长期更新，今天就上线。

## 关键资产

- `capture/screenshots/scroll-000-zh.png`
- `capture/screenshots/scroll-067-zh.png`
- `capture/screenshots/scroll-090-zh.png`
- `capture/assets/hero-stack.webp`
- `capture/assets/logo.webp`
- `capture/assets/avatars/*.webp`

## 工程结构

```text
shipsaas-promo-zh/
├── index.html
├── DESIGN.md
├── SCRIPT.md
├── STORYBOARD.md
├── narration.txt
├── narration.aiff
├── narration.wav
├── capture/
│   ├── screenshots/
│   └── assets/
└── compositions/
    ├── beat-1-hook.html
    ├── beat-2-boilerplate.html
    ├── beat-3-stack.html
    ├── beat-4-proof.html
    └── beat-5-cta.html
```
