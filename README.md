# ks-article-fact-check · 发稿前的最后一道闸 ✅

> *Two-track fact-checking for articles: source-vs-draft and external verification, fixes facts only.*

一篇稿子写完，最怕的不是错别字，是那种「看起来完全对」的错：头衔早换了、引号里的话其实是转述、数字多了一个零、两件事的先后顺序反了。读者不会指出来，他们只会默默把你从「可信」那一栏划掉。

这个 skill 就干一件事：**在你按下发布之前，把这些找出来。**

## 🔬 它怎么查

1. 📝 **拆声明清单** —— 通读全文，把人物、机构、头衔、引语、数字、比例、金额、事件、地点、时间线、出处逐条抽出来
2. 🔀 **两路独立核查，互不通气**
   - 一路对着你给的原始材料（报道、PDF、录音稿）逐条比，重点盯归属、数字、顺序、头衔
   - 一路上网找第一方资料（机构官网、原始论文、原始数据），关键结论要两个独立来源
   - 两路各写各的文件，谁也看不到谁的答案，也看不到你的预期
3. 🚦 **合并分级** —— 必改硬错误 / 轻度偏差 / 完全有据 / 未能核实（**「没搜到」绝不写成「已证伪」**）
4. ✍️ **出修正稿** —— 只修事实，不顺手润色。原稿保留，新稿另存

## 💬 你说什么，它给什么

你说：「核一下这篇公众号稿，原始报道在 sources/ 里」

它还你三个文件：两份核查报告（每条 ✅/⚠️/❌ 带证据摘录和位置）、一份合并总结（必改项的 before/after）、一份 `*-fact-checked.md` 修正稿。文风一个字不动。

## 🧠 为什么要两路互不通气

因为核查者知道「作者觉得哪里可疑」之后，就会只查那里。两路盲核，才能抓到作者自己都没怀疑的地方。

## 🧩 边界

- 核**你自己写的稿** → 这个
- 核**别人在网上吹的项目/数据** → [ks-deep-claim-audit](https://github.com/KaiSky0823/ks-deep-claim-audit)
- 审**一个博主整体靠不靠谱** → [ks-source-audit](https://github.com/KaiSky0823/ks-source-audit)

## ⚙️ 安装

```bash
# Claude Code
git clone https://github.com/KaiSky0823/ks-article-fact-check.git ~/.claude/skills/ks-article-fact-check
# Codex
git clone https://github.com/KaiSky0823/ks-article-fact-check.git ~/.agents/skills/ks-article-fact-check
```

## License

MIT © 2026 KaiSky0823
