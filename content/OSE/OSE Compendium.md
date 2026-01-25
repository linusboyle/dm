---
title: OSE 不全书
date: 2025-01-16
tags:
  - ose/list
aliases:
  - OSE 不全书
  - OSE 可用资源大全
---

此处收录的玩家资源以经典奇幻和高等奇幻为基础[^2]，选择性地加入一些第三方或自制内容。OSE SRD内的基础职业和法术见[[核心职业]]和[[核心法术]]。 

中文译文的版权归属译者，此处摘编仅限个人使用。

**Credits**

- 系统参考文档（[OSE SRD](https://oldschoolessentials.necroticgnome.com/srd/index.php/Main_Page)）/ 译文来自OSE・经典奇幻，白药君，亮君，ZzNoah，HXQXH，水肺，Ghost译
- [[德鲁伊]]职业及法术 / ZzNoah译
- 其他官方职业及法术 / 月狂译
- 第三方资源作者/译者见对应页

# **职业**

## 经典奇幻

```dataview
List from #ose/class and #src/ose/OSECF
```

## 高级奇幻

```dataview
list from #ose/class and #src/ose/oseaf 
```

## Carcass Crawler 杂志

```dataview
list from #ose/class and #src/ose/CC 
```

## 其他正式发表的职业

```dataview
List from #ose/class and !#src/ose/CC and !#src/ose/OSECF and !#src/ose/OSEAF and !#src/ose/HB
```

## **玩家自制/未经测试**

```dataview
List from #ose/class and #src/ose/HB
```

# **法术**

## 牧师法术

```dataview
Table without id cleric-spell-level as 环位, file.link as 法术 from  #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template")  sort cleric-spell-level
```


## 魔法师法术

```dataview
Table without id magic-user-spell-level as 环位, file.link as 法术 from  #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template")  sort magic-user-spell-level
```

## 德鲁伊法术

```dataview
Table without id druid-spell-level as 环位, file.link as 法术 from  #ose/spell where druid-spell-level >= 1 and !contains(file.path, "_template")  sort druid-spell-level
```

## 幻术师法术

```dataview
Table without id illusionist-spell-level as 环位, file.link as 法术 from  #ose/spell where illusionist-spell-level >= 1 and !contains(file.path, "_template")  sort illusionist-spell-level
```

## 其他

```dataview
List from #ose/spell/list 
```

[^2]: 高等奇幻允许种族和职业分离。我不使用这条可选规则，故不收录种族。