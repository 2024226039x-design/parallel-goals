# Parallel Goals

[English](README.md) | [简体中文](README.zh-CN.md)

Turn a raw task request into a filled build brief, one concrete top-level goal, independent parallel agent goals, and a synthesized final result.

## Install

```bash
git clone https://github.com/2024226039x-design/parallel-goals.git ~/.codex/skills/parallel-goals
```

## Use

Ask Codex to use `$parallel-goals`, then give it the task you want planned or executed through parallel goals.

Example:

```text
Use $parallel-goals to build a small dashboard for tracking weekly experiments.
```

## What It Does

- Fills a concrete build brief from the user's raw request.
- Defines a top-level goal with finishing criteria and verification.
- Splits work into independent agent goals when parallel work is useful.
- Synthesizes the results and keeps the main agent responsible for the final answer.

## Files

- `SKILL.md`: the skill instructions.
- `agents/interface.yaml`: interface metadata.

## License

MIT
