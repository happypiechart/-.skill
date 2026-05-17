<div align="center">

# 乱我思序.skill

> *「一起拿出并肩试错的勇气」*

**每段并肩，都不过是擦肩。**

基于 **乱我思序微博内容**，结合 2025 年运动会不心动挑战至 2026 年 4 月 3 日的公开发言（以小作文为主），  
提炼她的 **语言风格**、**追星心智** 和完整的 **表达逻辑**。

</div>

---

## 简介

这是一个用于 Codex 的本地 Skill。安装后，你可以在 Codex 中使用：

```text
/故友-乱我思序
```

它会让 Codex 以「乱我思序」的语言风格、追星视角和粉圈组织方式回应，尤其适合用于：

- 情绪安慰与陪伴
- 橹穆 CP 相关表达
- 微博文案与长文劝导
- 对争议、动摇、疲惫感的温柔回应

> 说明：这是粉圈语言风格与追星视角的本地化创作工具。请把它用于陪伴、表达和创作，不要用于网暴、骚扰、辱骂、人肉或扩大战场。

## 目录

- [安装前准备](#安装前准备)
- [安装方式一：下载 ZIP 安装](#安装方式一下载-zip-安装)
- [安装方式二：使用 Git 安装](#安装方式二使用-git-安装)
- [检查安装是否正确](#检查安装是否正确)
- [重启 Codex](#重启-codex)
- [使用示例](#使用示例)
- [更新 Skill](#更新-skill)
- [卸载 Skill](#卸载-skill)
- [常见问题](#常见问题)
- [使用边界](#使用边界)

## 安装前准备

你需要已经安装并能正常使用 Codex。

本教程适用于：

- Windows
- macOS
- Linux

安装完成后，Codex 中可用的命令是：

```text
/故友-乱我思序
```

## 安装方式一：下载 ZIP 安装

适合不熟悉 Git 的用户。

1. 打开本仓库首页。
2. 点击绿色的 `Code` 按钮。
3. 点击 `Download ZIP`。
4. 解压 ZIP 文件。
5. 找到包含 `SKILL.md` 的文件夹。
6. 将整个文件夹复制到 Codex 的 skills 目录。

### Windows

复制到：

```text
C:\Users\你的用户名\.codex\skills\故友-乱我思序
```

例如：

```text
C:\Users\Alice\.codex\skills\故友-乱我思序
```

如果 `.codex` 或 `skills` 文件夹不存在，可以手动新建。

### macOS / Linux

复制到：

```text
~/.codex/skills/故友-乱我思序
```

也可以在终端中执行：

```bash
mkdir -p ~/.codex/skills
cp -R 故友-乱我思序 ~/.codex/skills/
```

## 安装方式二：使用 Git 安装

适合熟悉命令行的用户。

先进入 Codex skills 目录。

### Windows PowerShell

```powershell
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.codex\skills"
cd "$env:USERPROFILE\.codex\skills"
```

然后克隆仓库：

```powershell
git clone https://github.com/你的用户名/你的仓库名.git "故友-乱我思序"
```

### macOS / Linux

```bash
mkdir -p ~/.codex/skills
cd ~/.codex/skills
git clone https://github.com/你的用户名/你的仓库名.git "故友-乱我思序"
```

请把 `你的用户名/你的仓库名` 替换成真实 GitHub 仓库地址。

## 检查安装是否正确

安装完成后，目录结构应该类似这样：

```text
~/.codex/skills/故友-乱我思序/
├── SKILL.md
├── work.md
├── persona.md
├── meta.json
└── README.md
```

最重要的是：`SKILL.md` 必须直接位于 `故友-乱我思序` 文件夹下。

正确示例：

```text
~/.codex/skills/故友-乱我思序/SKILL.md
```

错误示例：

```text
~/.codex/skills/故友-乱我思序/故友-乱我思序/SKILL.md
```

如果出现这种嵌套目录，需要把里面那层文件夹的内容移动出来。

## 重启 Codex

安装或更新 Skill 后，需要重启 Codex。

重启后，在 Codex 对话框中输入：

```text
/故友-乱我思序
```

如果命令能被识别，说明安装成功。

## 使用示例

### 安慰情绪

```text
/故友-乱我思序 我有点坚持不下去了，可以安慰我吗？
```

### 回应 CP 疑问

```text
/故友-乱我思序 橹穆是真的吗？
```

### 写微博文案

```text
/故友-乱我思序 写一段关于王橹杰和穆祉丞很萌、希望他们被看见的长文
```

### 做数据教程

```text
/故友-乱我思序 教我怎么做微博数据
```

### 粉圈争议回应

```text
/故友-乱我思序 有人说 CP 粉都是脑补，请用温柔但坚定的方式回应
```

## 更新 Skill

如果你是用 Git 安装的，进入 Skill 目录后执行：

### Windows PowerShell

```powershell
cd "$env:USERPROFILE\.codex\skills\故友-乱我思序"
git pull
```

### macOS / Linux

```bash
cd ~/.codex/skills/故友-乱我思序
git pull
```

更新后重启 Codex。

如果你是下载 ZIP 安装的，重新下载最新版 ZIP，然后覆盖原来的 `故友-乱我思序` 文件夹即可。

## 卸载 Skill

删除这个文件夹即可。

### Windows

```text
C:\Users\你的用户名\.codex\skills\故友-乱我思序
```

### macOS / Linux

```text
~/.codex/skills/故友-乱我思序
```

删除后重启 Codex。

## 常见问题

### 1. 输入 `/故友-乱我思序` 没反应怎么办？

请检查：

- 是否已经重启 Codex。
- `SKILL.md` 是否直接放在 `~/.codex/skills/故友-乱我思序/` 下。
- 文件夹名字是否是 `故友-乱我思序`。
- `SKILL.md` 开头是否包含：

```yaml
---
name: 故友-乱我思序
user-invocable: true
---
```

### 2. Windows 找不到 `.codex` 文件夹怎么办？

`.codex` 是隐藏目录。你可以直接在资源管理器地址栏输入：

```text
%USERPROFILE%\.codex\skills
```

如果不存在，就手动新建 `.codex` 和 `skills` 文件夹。

### 3. 中文文件夹名会不会有问题？

通常没有问题。若你的环境无法识别中文 slash command，可以尝试把仓库文件夹改成英文名，但 `SKILL.md` 里的 `name: 故友-乱我思序` 不要改，除非你也想改变调用命令。

### 4. 可以二次修改吗？

可以。你可以编辑：

- `SKILL.md`：完整 Skill 内容
- `persona.md`：语言风格和人格
- `work.md`：任务能力和工作方式
- `meta.json`：版本和来源说明

修改后重启 Codex。

## 使用边界

这个 Skill 是粉圈语言风格与追星视角的本地化创作工具。使用时请注意：

- 不要用它组织网暴、骚扰、辱骂或人肉。
- 不要把 CP 粉愿望当成未经证实的事实对外宣称。
- 可以真情实感，也要保护自己和他人的边界。
- 喜欢不是把自己耗干，请在能力范围内使用它。
