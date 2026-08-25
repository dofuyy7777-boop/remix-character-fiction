# remix-character-fiction

同人文大乱炖：把作品 A 的人物灵感与作品 B 的冲突结构重新融合，创作人物驱动的现代原创短篇小说。

## 功能

- 提炼角色的欲望、恐惧、性格矛盾和关系模式
- 借鉴另一部作品的抽象冲突结构，而非照搬剧情
- 根据发布平台、题材和篇幅调整叙事
- 联网核验人物与作品信息后再生成创作任务卡
- 检查原创化距离、情节因果和成稿质量

## 安装

将仓库克隆到 Codex Skills 目录：

```bash
git clone https://github.com/dofuyy7777-boop/remix-character-fiction.git ~/.codex/skills/remix-character-fiction
```

安装后重新启动 Codex。

## 使用

在 Codex 中输入：

```text
$remix-character-fiction
```

也可以直接附上创作要求，例如：

```text
使用 $remix-character-fiction，把作品 A 中人物 a 的人物特点，
与作品 B 中某个故事的冲突结构结合起来，创作一篇现代短篇小说。
```

Skill 会收集作品、人物、参考情节、发布平台、题材和篇幅等信息，完成联网核验并生成任务卡；确认后开始创作。

## 目录结构

```text
remix-character-fiction/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── engines-and-originality.md
    └── platform-and-quality.md
```

## 版权说明

本仓库的 MIT License 仅适用于仓库中的 Skill 文件，不代表授予任何原作、角色、作品名称或第三方素材的相关权利。使用者应自行遵守适用的版权规则和发布平台规范。

## License

[MIT](LICENSE)
