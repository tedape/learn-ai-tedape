# 疯狂的一天：我用 AI 完成了第一次开源提交

![疯狂的一天徽章](https://img.shields.io/badge/crazy-day-FF69B4)

## 一、今天为什么疯狂

今天我做了一件以前觉得很难的事：注册 GitHub 账号，并把写好的文章提交到远程仓库。

以前我总觉得开源离我很远，今天才发现只要按步骤操作，零基础也能完成。

### 1.1 我完成了三个第一次

- 第一次拥有属于自己的 GitHub 用户名 `tedape`
- 第一次创建了公开仓库 `learn-ai-tedape`
- 第一次用命令行把文件推送到 GitHub

## 二、我学会的命令

下面是我今天敲过的命令，每一行都值得记住：

```bash
git init
git add crazy-day.md
git commit -m "docs: add crazy day article"
git branch -M main
git remote add origin https://github.com/tedape/learn-ai-tedape.git
git push -u origin main
```

### 2.1 命令难度对照表

| 命令 | 作用 | 难度 |
| --- | --- | --- |
| `git init` | 把当前文件夹变成 git 仓库 | 1 星 |
| `git add` | 把文件放进暂存区 | 2 星 |
| `git commit` | 把暂存区内容存成一个版本 | 2 星 |
| `git push` | 把本地版本推送到 GitHub | 3 星 |

## 三、我记住的三条排版规范

写这篇文档时，我用三条规范检查了每一个句子：

- 中英文之间要加空格，例如 GitHub 账号
- 中文和数字之间要加空格，例如 3 个命令
- 数字和单位之间不加空格，例如 8GB

记住这三条，文章看起来立刻专业很多。

### 3.1 标点符号的规则

中文语境下必须使用全角标点，例如打开你的 iPhone，然后点击“设置”。

英文和代码语境下使用半角标点，例如 `git commit -m "hello"`。

## 四、参考资料

- [GitHub 官方文档](https://docs.github.com/)
- [Markdown 语法指南](https://www.markdownguide.org/)
- [苹果官网](https://www.apple.com.cn/)

### 4.1 明天的目标

1. 学会阅读 git 的提交历史
2. 尝试修改文章后再次提交
3. 给仓库加上合适的描述

> 疯狂不是胡来，而是把“我不会”变成“我试过了”。
