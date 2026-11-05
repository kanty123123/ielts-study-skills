[Uploading README.md…]()
# IELTS Study Skills｜雅思备考提示词

面向中文母语进阶学习者的外刊英中对照精读技能。当前项目包含一个技能：`foreign-press-reading`。

## 下载与安装

[下载完整Skill安装包](ielts-study-skills.zip)。解压后将`skills/foreign-press-reading`目录复制到个人技能目录（通常为`~/.codex/skills/`），保留全部子目录。

## 使用示例

```text
使用 $foreign-press-reading
学习目标：雅思阅读与表达迁移
基础：B2
学习时间：25分钟
输入：[粘贴英文文章或指定节选]
```

默认交付Markdown讲义，按英文原文、完整中文译文、随句简注的顺序组织；少量高价值用法展开迁移，并按需补背景、回收重点和自测。具体规则以SKILL.md为准。

## 源文件

- `skills/foreign-press-reading/SKILL.md`：技能规则。
- `skills/foreign-press-reading/agents/openai.yaml`：技能展示信息。
- `skills/foreign-press-reading/references/verification.md`：来源与用法核验参考。
- `skills/foreign-press-reading/references/lesson-example.md`：用于校准版式与讲解深度的示例。

## 更新方式

修改相应源文件，检查本地引用与讲义效果，再重新打包同名ZIP，提交源文件与安装包；需要在当前电脑使用时另行同步本地安装目录。

## 范围与依赖

本仓库仅保存Skill及其运行参考，未包含项目work、outputs、学习记录、个人配置或账号密钥。技能本身为文本规则；按任务需要使用当前环境的搜索与文档读取工具。示例中的外刊节选与相关来源链接保留原有归属，不能将示例选文视为后续课程固定内容。

导出日期：2026-11-05；源Skill未设置版本号，本次用导出日期与Git提交记录标识。
