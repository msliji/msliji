# 热门开源项目合集 · Trending Open Source

> 收录 2026 年 10 月至 11 月 GitHub 上**涨星最快**的 3 个项目，以 **Fork** 形式归于本账号，便于学习与二次开发。
>
> 数据快照：2026-11-03

## 项目一览

| # | 项目 | 星标 | 语言 | 许可证 | 简介 |
|:-:|---|--:|---|---|---|
| 1 | [cleanyourtv](https://github.com/msliji/cleanyourtv) | 50.9k | Python | 自定义 | 通过 Wi-Fi 给 Android TV / Google TV 做「减负」清理，并换上 Apple TV 风格的首页 |
| 2 | [DeepInfer](https://github.com/msliji/DeepInfer) | 25.1k | Python | Apache-2.0 | DeepSeek 模型的高性能、大规模推理框架 |
| 3 | [anatomy](https://github.com/msliji/anatomy) | 24.3k | JavaScript | MIT | 生成精确、可交互的等距插画（含 WebGL 着色器与 3D 效果）的 Agent 技能 |

---

## 1. cleanyourtv

**上游**：https://github.com/Gathin23/cleanyourtv
**Fork**：https://github.com/msliji/cleanyourtv

> Debloat any Android or Google TV over Wi-Fi and get an Apple TV-style home.

通过 Wi-Fi（ADB）连接电视设备，卸载预装臃肿应用，并把首页替换成接近 Apple TV 的清爽体验。

**标签**：`adb` `adblock` `android-tv` `android-tv-launcher` `apple-tv`

---

## 2. DeepInfer

**上游**：https://github.com/deepseek-ai/DeepInfer
**Fork**：https://github.com/msliji/DeepInfer

> DeepInfer: High-performance, large-scale inference framework for DeepSeek models.

面向 DeepSeek 系列模型的大规模推理框架，关注吞吐与延迟表现。

**许可证**：Apache-2.0

---

## 3. anatomy

**上游**：https://github.com/wheresryan22/anatomy
**Fork**：https://github.com/msliji/anatomy

> An agent skill for creating detailed, interactive isometric illustrations of real-world machines and complex systems. Generates polished SVGs with optional WebGL shaders and 3D effects.

一个 Agent 技能：把真实机器与复杂系统画成精细的等距插画，输出打磨过的 SVG，可选 WebGL 着色器与 3D 效果。

**标签**：`agent-skill` `svg` `visualization`
**许可证**：MIT

---

## 说明

- 本仓库中的三个项目均为 **Fork**，**代码版权与署名归原作者所有**，本仓库不主张任何著作权。
- 如需使用、修改或分发，请遵守各项目自身的开源许可证条款。
- 本项目仅为聚合索引，方便集中查看与跟进上游更新。

## 如何同步上游更新

```bash
# 以 cleanyourtv 为例
git clone https://github.com/msliji/cleanyourtv.git
cd cleanyourtv
git remote add upstream https://github.com/Gathin23/cleanyourtv.git
git fetch upstream
git merge upstream/main
git push origin main
```

---

<sub>Generated with WorkBuddy · 2026-11-03</sub>
