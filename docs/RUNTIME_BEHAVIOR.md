# Runtime behavior / 运行时行为

## Needs-user-input alert / 需要用户介入提醒

Codex identifies **Needs input** when a chat requires an approval, answer, permission decision, or another user decision. This pet assigns that state to atlas row 6 (`waiting`): Rex repeatedly crouches, jumps, and waves both arms until Codex changes the chat out of the Needs input state.

当某个聊天需要批准、回答、权限决定或其他用户选择时，Codex 会标为 **需要输入**。本宠物将该状态映射至图集第 6 行（`waiting`）：Rex 会持续循环下蹲、跳起与双臂挥舞，直到 Codex 将聊天切换出“需要输入”状态。

The pet asset is an indicator, not a task controller: entering the chat and providing the required approval, answer, permission, or choice is what lets the task resume.

宠物资产只负责提示，不会自行控制任务；进入聊天并给出所需批准、回答、权限或选择，才会让任务继续执行。

Official status reference / 官方状态说明：[OpenAI Docs — Pets](https://developers.openai.com/zh-Hans/docs/pets).
