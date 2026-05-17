# loading-to-thinking

> 🤖 **The official guide to AI productization.**
> 请把 `加载中` 改成 `思考中....`

The single most important UX upgrade of 2025: rename `Loading...` to `Thinking...`.

Congrats — you have an AI product now.

This is the spinner that comes with it. **36 thinking animations × 3 colors, in one HTML file. Zero build.**

![hero](docs/hero.png)

## 🎯 Live Demo

→ **[edison7009.github.io/loading-to-thinking](https://edison7009.github.io/loading-to-thinking)**

## ✨ What's inside

- **36 animations** — 3 rows × 12 wave patterns, all running in sync
- **Click any cell to select** — code export below updates instantly
- **3 row colors** — each row has its own pickable color
- **3 export formats** — `HTML + CSS` / `React + Tailwind` / `Pure CSS`
- **中 / EN** bilingual UI (toggle top-right)
- **One HTML file** — no npm, no build step. Drop it on GitHub Pages, Vercel, or your toaster.

## 🚀 How to use

1. Open [`index.html`](./index.html) — locally or via the live demo
2. Pick a row color (defaults: `emerald` · `pink` · `cyan`)
3. Click any cell in the wall — its combo gets selected
4. Copy the generated code in your preferred format
5. In your app, **replace "Loading..." with "Thinking...."**

That's it. **You are now an AI company.**

## 💡 Why this exists

In 2025, the difference between *your app* and *your AI app* is two CSS properties and a string replacement:

```diff
- <div>Loading...</div>
+ <div class="ai-thinking">
+   <span>Thinking...</span>
+ </div>
```

This tool is half a joke and half a working spinner library. Use it for either.

## 🎨 The 12 wave patterns

All run on the same keyframe (`@keyframes aiThink`) — only each dot's `animation-delay` differs.

| Pattern | Direction |
|---|---|
| `Wave-LR` / `Wave-RL` | Horizontal sweep ↔ |
| `Wave-TB` / `Wave-BT` | Vertical sweep ↕ |
| `Wave-Diag-TL` / `Wave-Diag-BR` | Diagonal sweep |
| `Ripple` | Center-out pulse |
| `Pulse` | All 9 in sync |
| `Snake-CW` / `Snake-CCW` | Spiral path |
| `Wave-Double` / `Wave-Spiral` | Layered waves |

## 🛠 Tech

- Single `index.html`, ~1500 lines
- Vanilla JS + Tailwind via CDN
- No build, no dependencies, no `package.json`
- `localStorage` for language preference

## 🙏 Inspired by

- **Anthropic's** 9-dot brand visual language
- [tobiasahlin/SpinKit](https://github.com/tobiasahlin/SpinKit) — the original spinner-wall showcase
- [loading.io](https://loading.io) — multi-format export pioneer

This repo's contribution to the genre: **the niche of AI thinking indicators specifically.** Old spinners spin. We make dots think.

## 📜 License

MIT © [Edison](https://github.com/edison7009)

---

<details>
<summary>中文版</summary>

请把 `加载中` 改成 `思考中....`。恭喜,你的产品现在是 AI 产品了。

这是配套的 spinner 生成器。**36 个 AI 思考动画 × 3 种颜色,一份 HTML 文件搞定**。

### 特性

- **36 种动画同步演奏** — 3 行 × 12 种波形,同步预览
- **点击任意 cell 选中** — 下方代码立刻更新
- **3 行独立配色** — 每行一个颜色,右侧 picker 控制
- **3 种导出格式** — `HTML + CSS` / `React + Tailwind` / `纯 CSS`
- **中 / EN 双语** — 右上角切换,记忆到 localStorage
- **零构建** — 一份 HTML,丢哪都能跑

### 用法

打开 `index.html` → 选 cell → 复制代码 → 把 `加载中` 改成 `思考中....`。**完了**。

### 灵感来源

- **Anthropic** 的 9 点品牌视觉
- [SpinKit](https://github.com/tobiasahlin/SpinKit) — spinner 展示墙的鼻祖
- [loading.io](https://loading.io) — 多格式导出的先驱

老式 spinner 在转,我们让点在思考。

</details>
