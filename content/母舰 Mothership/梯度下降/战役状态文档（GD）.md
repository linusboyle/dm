---
title: 战役状态文档（GD）
date: 2026-08-12
tags:
aliases:
gd_day: 1
gd_time: 9:00
---

## PC

```base
filters:
  and:
    - file.inFolder("母舰 Mothership/梯度下降/PC")
properties:
  file.name:
    displayName: 名称
  note.player:
    displayName: 玩家
  note.class:
    displayName: 职类
  note.stress:
    displayName: 压力
  note.bends:
    displayName: 潜压
views:
  - type: table
    name: PC
    order:
      - file.name
      - player
      - class
      - stress
      - bends
      - status

```

已找到神器：



## Idea

1. 22C 电梯的电梯井藏着一件神器
2. 22C 'Olham was here' -> 'PC name was here'
3. 到达钟摆站并休息->从冷藏室醒来
4. 团灭同理
5. 潜压检定在每次游戏结束时进行，私下告知（结合[[Memory Generation Table]]）
