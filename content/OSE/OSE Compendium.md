---
title: OSE 不全书
date: 2025-01-16
tags:
  - ose/list
aliases:
  - OSE 不全书
  - OSE 可用资源大全
---

本站收录的玩家资源以经典奇幻和高等奇幻为基础[^2]，选择性地加入一些第三方或自制内容。OSE SRD内的基础职业和法术见[[核心职业]]和[[核心法术]]。 

**Credits**

- 系统参考文档（[OSE SRD](https://oldschoolessentials.necroticgnome.com/srd/index.php/Main_Page)）/ 译文来自OSE・经典奇幻，白药君，亮君，ZzNoah，HXQXH，水肺，Ghost译
- 第三方资源作者/译者见对应页

# **职业**

## 经典奇幻

<!-- QueryToSerialize: List from #ose/class and #src/ose/OSECF -->
<!-- SerializedQuery: List from #ose/class and #src/ose/OSECF -->
- [[魔法师]]
- [[精灵]]
- [[矮人]]
- [[盗贼]]
- [[牧师]]
- [[战士]]
- [[半身人]]
<!-- SerializedQuery END -->

## 高级奇幻

<!-- QueryToSerialize: List from #ose/class and #src/ose/OSEAF -->
<!-- SerializedQuery: List from #ose/class and #src/ose/OSEAF -->
- [[骑士]]
- [[野蛮人]]
- [[游侠]]
- [[德鲁伊]]
- [[幻术师]]
- [[圣武士]]
- [[吟游诗人]]
- [[刺客]]
- [[侏儒]]
<!-- SerializedQuery END -->

## Carcass Crawler 杂志


<!-- QueryToSerialize: List from #ose/class and #src/ose/CC -->

## 其他正式发表的职业


<!-- QueryToSerialize: List from #ose/class and !#src/ose/CC and !#src/ose/OSECF and !#src/ose/OSEAF and !#src/ose/HB -->

## **玩家自制/未经测试**

<!-- QueryToSerialize: List from #ose/class and #src/ose/HB -->

# **法术**

## 牧师法术

<!-- QueryToSerialize: Table without id cleric-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template") group by cleric-spell-level -->
<!-- SerializedQuery: Table without id cleric-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template") group by cleric-spell-level -->

| 环位 | 法术 |
| -- | -- |
<!-- SerializedQuery END -->

## 魔法师法术

<!-- QueryToSerialize: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->
<!-- SerializedQuery: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->

| 环位 | 法术 |
| -- | -- |
<!-- SerializedQuery END -->

## 德鲁伊法术

<!-- QueryToSerialize: Table without id druid-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where druid-spell-level >= 1 and !contains(file.path, "_template") group by druid-spell-level -->
<!-- SerializedQuery: Table without id druid-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where druid-spell-level >= 1 and !contains(file.path, "_template") group by druid-spell-level -->

| 环位 | 法术 |
| -- | -- |
<!-- SerializedQuery END -->

## 幻术师法术

<!-- QueryToSerialize: Table without id illusionist-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where illusionist-spell-level >= 1 and !contains(file.path, "_template") group by illusionist-spell-level -->
<!-- SerializedQuery: Table without id illusionist-spell-level as 环位, rows.file.link as 法术 from  #ose/spell where illusionist-spell-level >= 1 and !contains(file.path, "_template") group by illusionist-spell-level -->

| 环位 | 法术 |
| -- | -- |
<!-- SerializedQuery END -->

## 其他

<!-- QueryToSerialize: List from #ose/spell/list -->

[^2]: 高等奇幻允许种族和职业分离。我不使用这条可选规则，故不收录种族。