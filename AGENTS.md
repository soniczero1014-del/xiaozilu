# Project Instructions

- 本项目后续每次任务完成后，都要使用 `feishu-codex-notify` skill 向飞书 `codex通知` 群发送完成信息和简单摘要。
- 默认发送脚本：`/Users/admin/.codex/skills/feishu-codex-notify/scripts/send_completion.py`
- 默认目标：`feishu:oc_4362f430777f325718023750a66e6470`
- 消息格式固定为：
  - `已完成：<task title>`
  - `摘要：<one short factual summary>`
- 任务只要真实完成且已验证，就发送通知。
- 如果任务被阻塞、只完成了一部分，或者没有实际变更，也要发送，但摘要里要明确写出当前状态和下一步。
- 不要提前发送；等任务结束后再发。
