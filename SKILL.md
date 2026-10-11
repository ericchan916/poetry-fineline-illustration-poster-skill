---
name: poetry-fineline-illustration-poster
description: 新中式古诗词细线插画海报：把一首古诗词的景物、动作与情感转化为高俯视、散点透视的新中式细线设色装饰插画海报（石青、石绿、黛青、朱砂、赭红、象牙白）。当用户提到"古诗词海报 / 诗词插画 / 新中式细线设色"或给出一首古诗要做海报时使用。Use when the user asks for a Chinese poetry poster, a poem illustration, or a new-Chinese fine-line colored illustration — turns one classical poem into a single 9:16 textbook-grade fine-line illustration poster with clear visual narrative.
license: MIT
---

# 新中式古诗词细线插画海报 · Chinese Poetry Fine-line Illustration Poster

把诗里的景、事、情，画成一幅叙事清晰、留白有诗意的新中式细线设色插画海报。
Turn a classical poem's scenery, actions and emotions into one fine-line, flat-color Eastern illustration poster.

## 输入 · Inputs

```
【古诗词】：标题、作者、原文
【核心场景】：（填写或由 AI 提取）
【关键意象】：（填写或由 AI 提取）
【视觉关系】：如 红杏越墙、蜻蜓立荷、牧童指路
【主色调】：东方传统配色
【画幅比例】：9:16（默认）
```

## 使用规则 · Agent rules
- **不要追问**。只给了诗名或原文时，自行从诗中提取核心场景、关键意象、视觉关系与主色调；画幅缺省 9:16。
- **核对原文**：标题、作者、原文必须准确。只给诗名时使用公认的通行版本；不确定时宁可只用确定的句子，**绝不编造或改写诗句**。用户给的原文若有明显错字，按通行版本校正。
- 内部完成分析，不展示过程，只输出一张海报。环境不能生图时，输出已填好的 [prompt.md](prompt.md) 提示词供用户粘贴到 ChatGPT / 其他图像模型。

示例见 [examples/poems.md](examples/poems.md)。

## 核心规则 · Core rules

### 目标 · Goal
以诗为本，创作一幅新中式细线设色装饰插画海报，将诗中景物、动作与情感转化为有清晰视觉叙事的东方场景。

### 视角与构图 · View & composition
- 高俯视视角 + 东方散点透视 + 现代平面构图。
- 构图随诗意调整，突出核心意象；层次清晰，疏密有序。

### 造型 · Rendering
- **树冠**：柔软蓬松、云团般的色块，边缘为细腻粉状点簇；内部是纤细连贯的墨黑枝干。
- **建筑**：精细工笔线描，青绿瓦顶、暖白墙面、朱红木构。
- **人物、动物、植物**：统一的细线 + 平涂设色；动态自然、结构准确、空间关系清楚。
- **地面与水面**：大面积暖米白留白，少量墨色阴影与简洁细线。

### 色彩 · Color
石青、石绿、黛青、朱砂、赭红、象牙白；色彩饱满均匀、哑光干净，带轻微纸张质感。

### 文字 · Text
大号暖白色中文标题；小号竖排诗词原文；作者落款；几枚红色印章。

### 避免 · Avoid
写实摄影、3D、动漫风、浓重水墨晕染、厚重油画肌理、复杂背景、过度颗粒、人为做旧；（并确保诗文无错字、无乱码）。

### 最终效果 · Final quality
教科书级精致插画，东方美学，留白富有诗意，叙事生动。
