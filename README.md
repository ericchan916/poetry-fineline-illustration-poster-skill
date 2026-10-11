# 新中式古诗词细线插画海报 Skill / Chinese Poetry Fine-line Illustration Poster Skill

输入一首古诗词，生成一张新中式细线设色装饰插画海报：高俯视、散点透视、云团树冠、工笔建筑、大面积留白，教科书级精致插画。

## 它能做什么
- 把诗中的景物、动作与情感转化为有清晰叙事的东方场景
- 只给诗名也能用：自动提取核心场景、关键意象与视觉关系
- 核对诗文，不编造诗句
- 大号暖白标题、竖排原文、作者落款、红色印章

## 安装
**作为 Agent Skill（Claude Code / Cursor / Codex 等）**：

```bash
git clone https://github.com/ericchan916/poetry-fineline-illustration-poster-skill.git
cp -r poetry-fineline-illustration-poster-skill ~/.claude/skills/poetry-fineline-illustration-poster
# 或 ~/.cursor/skills/、~/.codex/skills/ 等
```

**在 ChatGPT / 其他图像模型中使用**：复制 [`prompt.md`](prompt.md) 里的完整提示词，填入诗词即可。

## 使用示例
```
【古诗词】：小池 / 杨万里 / 泉眼无声惜细流，树阴照水爱晴柔。小荷才露尖尖角，早有蜻蜓立上头。
【视觉关系】：蜻蜓立荷
【画幅比例】：9:16
```
或只写：`【古诗词】：江雪 / 柳宗元`

更多示例见 [`examples/poems.md`](examples/poems.md)。

## 配色
| 色名 | 用途示例 |
|---|---|
| 石青 | 瓦顶、水面、远山 |
| 石绿 | 树冠、草地、瓦顶 |
| 黛青 | 远山、阴影、枝干 |
| 朱砂 | 木构、印章、点睛 |
| 赭红 | 土地、衣饰、木质 |
| 象牙白 | 墙面、留白、标题 |

## English
**Chinese Poetry Fine-line Illustration Poster** turns a classical Chinese poem into one 9:16 new-Chinese fine-line, flat-color illustration poster with a high overhead view, scattered perspective, poetic negative space and accurate verse text. Copy the folder into your agent's skills directory, or paste `prompt.md` into ChatGPT or any image model.

## License
MIT © 2026 Joy Robinson — 见 [LICENSE](LICENSE)。生成图片的使用请同时遵守你所用图像模型的服务条款。
