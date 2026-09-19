# Project scope and reproduction notes / 项目范围与复现说明

## Delivered asset / 已交付资产

The repository contains the final Codex v2 animation atlas, a pet manifest, GIF previews, and the structural validation report.

本仓库包含最终 Codex v2 动画精灵图、宠物配置、GIF 动作示意与结构校验报告。

## Motion mapping / 动作映射

| Atlas row / 精灵图行 | English | 中文 |
| --- | --- | --- |
| 0 | Livelier low-frequency idle: breathing, body bob, chest-height claw lifts, and toe/weight shifts | 更有生命力的低频待机：呼吸、身体轻摆、抬至胸前的手爪收放与脚尖/重心变化 |
| 1 | Move right while dribbling one ball | 向右贴地带球 |
| 2 | Move left while dribbling one ball | 向左贴地带球 |
| 3–5, 8 | Waving, jumping, failed, review | 挥手、跳跃、失败、复核 |
| 6 | Needs-user-input alert: looping two-arm wave and jump for approval, permission, answer, or decision | 需要用户介入提醒：等待批准、权限、回答或选择时循环双臂挥舞与跳跃 |
| 7 | Working loop with one-ball juggling | 工作时的单球颠球循环 |
| 9–10 | Sixteen look directions | 十六个注视方向 |

## Reproduction boundary / 复现边界

This project publishes final derived pet assets only. It intentionally excludes all supplied reference photographs, generation prompts, temporary decoded strips, and local installation state.

本项目仅发布最终派生的宠物资产，刻意不包含用户提供的参考照片、生成提示词、临时拆帧文件与本地安装状态。

## Acceptance record / 验收记录

The spritesheet was deterministically assembled, chroma-edge despilled, and validated as a Codex v2 8 × 11 atlas. Motion previews were reviewed for the requested idle, needs-user-input alert, juggling, and dribbling semantics.

精灵图已通过确定性装配、色键边缘去溢色与 Codex v2 的 8 × 11 图集校验。动作示意已针对所需的待机律动、需要用户介入提醒、颠球与带球语义进行检查。
