# remix-character-fiction

同人文大乱炖：把作品 A 的人物灵感与作品 B 的冲突结构重新融合，创作人物驱动的现代原创短篇小说。

## 功能

- 提炼角色的欲望、恐惧、性格矛盾和关系模式
- 借鉴另一部作品的抽象冲突结构，而非照搬剧情
- 根据发布平台、题材和篇幅调整叙事
- 联网核验人物与作品信息后再生成创作任务卡
- 检查原创化距离、情节因果和成稿质量

## 安装

### 推荐：复制给 AI 安装

如果你使用的 AI 工具支持 Skills 和读取 GitHub 仓库，请将下面整段话复制给它：

```text
请从 https://github.com/dofuyy7777-boop/remix-character-fiction 安装名为 remix-character-fiction 的 Skill。请将仓库中的 SKILL.md、agents 和 references 完整安装到你所使用的 Skills 目录；安装完成后，告诉我是否安装成功，以及应该如何调用它。
```

不同工具可能会要求你确认下载、文件写入或重启。按照界面提示操作即可。如果工具不支持安装外部 Skills，它会提示无法完成。

### 手动安装

先克隆仓库：

```bash
git clone https://github.com/dofuyy7777-boop/remix-character-fiction.git
```

然后：

1. 将整个 `remix-character-fiction` 文件夹放入所用 AI 工具的 Skills 目录，或通过该工具的 Skill 导入功能选择此文件夹。
2. 确认该目录中直接包含 `SKILL.md`、`agents/` 和 `references/`，不要只复制 `SKILL.md`。
3. 按照工具提示重新加载 Skills 或重启工具。
4. 在技能列表中确认出现 `remix-character-fiction`。

具体的 Skills 目录和导入方式取决于所使用的工具，请参考对应工具的文档。

## 使用

安装成功后，可以先复制下面这句话测试调用：

```text
请使用 remix-character-fiction，告诉我创作一篇故事需要提供哪些信息。暂时不要开始创作。
```

正式创作时，可以直接复制并填写下面的模板：

```text
请使用 remix-character-fiction：
作品 A：
人物 a：
作品 B：
参考故事或场景：
发布平台：
小说题材：自动推荐
大致篇幅：自动推荐
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
