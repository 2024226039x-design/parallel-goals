# Parallel Goals

[English](README.md) | [简体中文](README.zh-CN.md)

把原始任务请求转换成完整 build brief、一个明确顶层目标、多个可并行执行的 agent 子目标，并汇总最终结果。

## 安装

```bash
git clone https://github.com/2024226039x-design/parallel-goals.git ~/.codex/skills/parallel-goals
```

## 使用

让 Codex 使用 `$parallel-goals`，然后给出你希望通过并行目标规划或执行的任务。

示例：

```text
Use $parallel-goals to build a small dashboard for tracking weekly experiments.
```

## 功能

- 从用户的原始请求中填出具体 build brief。
- 定义带完成标准和验证方式的顶层目标。
- 在并行工作有价值时，把任务拆成独立 agent 子目标。
- 汇总结果，并让主 agent 对最终答案负责。

## 文件

- `SKILL.md`：skill 指令。
- `agents/interface.yaml`：接口元数据。

## 许可证

MIT
