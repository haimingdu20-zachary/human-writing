# Human Writing

一个面向中文内容创作的 Codex / ChatGPT Skill，帮助用户从零散想法出发，共创选题、核准材料、搭建结构，并写出事实准确、表达自然的中文内容。

## 功能

- 通过多轮对话收束主旨和选题
- 在写作前检查材料是否足以支撑篇幅
- 区分现实写作、虚构创作和混合创作
- 支持专业产品、健康科技、研究数据和图片证据
- 约束常见的模型化表达，保留自然中文节奏

## 安装

把本仓库复制到你的 Skills 目录，并确保目录名为 `human-writing`。

```text
human-writing/
├── SKILL.md
├── agents/openai.yaml
├── assets/icon.svg
└── references/professional-evidence.md
```

## 使用

在支持 Skills 的产品中调用 `$human-writing`，然后提供你的想法、素材或写作目标。

示例：

```text
使用 $human-writing，帮我把最近关于 AI 写作的一些零散想法收束成一个适合公众号的选题。
```

## 当前版本说明

本仓库按原始压缩包发布。`SKILL.md` 中提到的其他参考文件和检查脚本未包含在原始包内，因此相关扩展规则目前不可用；已有的核心规则和 `professional-evidence.md` 可以正常阅读与复用。

## 许可证

[MIT](LICENSE)
