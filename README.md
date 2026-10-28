# build-character-diorama

一个帮助 AI 编程助手从原创角色与场景设定出发，制作并逐轮验收可交互微缩场景网页的 skill。

## 安装

从本仓库的 Code 按钮复制克隆地址，替换下面的“仓库克隆地址”，按使用的工具选择一条命令运行。

Claude Code：

```bash
git clone "仓库克隆地址" ~/.claude/skills/build-character-diorama
```

Codex：

```bash
git clone "仓库克隆地址" ~/.codex/skills/build-character-diorama
```

仓库根目录就是 skill 文件夹，包含 `SKILL.md`，无需再移动子目录。

## 开始使用

开场提示词（与 `agents/openai.yaml` 中的 `default_prompt` 一致）：

```text
使用 $build-character-diorama 为一个全新角色制作可交互的微缩场景，先明确风格与动作，再生成素材、搭建场景并实际验收。
```

## 包含什么

这个方法包只有文字：`SKILL.md`、`agents/openai.yaml` 和 `references/` 下的 8 篇参考文档，内容来自 v9。

不包含素材、角色图、场景代码或成品作品。使用时需要为自己的角色和场景准备或生成素材。

## 许可证

采用 [MIT License](LICENSE)。

## English

A text-only skill for AI coding assistants to create and iteratively validate interactive character diorama webpages. Clone this repository into `~/.claude/skills/build-character-diorama` for Claude Code or `~/.codex/skills/build-character-diorama` for Codex. It includes workflow guidance and reference documents, with no artwork, assets, or scene code. Licensed under the MIT License.
