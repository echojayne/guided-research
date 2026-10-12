# Guided Research · 引导式调研

通过关键追问、定向检索和证据分析，逐步明确调研问题、范围与结论，最终生成符合所附模板的一篇飞书调研报告。

主技能保持简短，报告模板在组织正文时按需读取。研究方向、科研问题和工程选型分别采用相应的检索来源；配置检查按实际使用的能力进行。

## 文件

- `SKILL.md`：引导流程、来源选择、收敛判断和飞书交付要求。
- `references/report-template.md`：报告章节、表格字段和交付检查。
- `agents/openai.yaml`：技能界面入口。

## 安装与使用

将仓库放入自己的技能目录，例如：

```bash
git clone https://github.com/echojayne/guided-research.git ~/.codex/skills/guided-research
```

使用示例：

```text
用 $guided-research 调研如何加速 RAG 的向量检索。
先帮我明确目标与约束，逐步收敛方案，最终生成飞书调研报告。
```

## 运行依赖

需要具备检索、阅读原始资料和飞书文档读写能力。本仓库提供流程与模板，依赖工具分别安装、配置。

- 学术检索：使用当前环境中的 `nature-academic-search` 技能。
- 工程检索：使用可用的网页或 GitHub 检索工具，优先官方资料、代码和实践证据。
- 飞书交付：`lark-cli`，以及 `lark-shared`、`lark-doc` 技能；读取或编辑嵌入电子表格时使用 `lark-sheets`。

初版已通过技能结构与引用检查；完整调研流程仍需结合真实主题试用。飞书授权不可用时保存本地进度，在线写入并回读成功后再报告交付完成。
