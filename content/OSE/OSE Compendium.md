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

```base
filters:
  and:
    - file.tags.contains("#src/ose/OSECF")
    - file.tags.contains("#ose/class")
properties:
  file.name:
    displayName: Name
views:
  - type: list
    name: Table
    order:
      - file.name

```

## 高级奇幻

```base
filters:
  and:
    - file.tags.contains("#ose/class")
    - file.tags.contains("#src/ose/OSEAF")
views:
  - type: list
    name: List
    order:
      - file.name

```

%%## Carcass Crawler 杂志

```base
filters:
  and:
    - file.tags.contains("#ose/class")
    - file.tags.contains("#src/ose/CC")
views:
  - type: list
    name: List
    order:
      - file.name

```

## 其他正式发表的职业

```base
filters:
  and:
    - file.tags.contains("#ose/class")
    - not:
        - file.tags.contains("#src/ose/CC")
        - file.tags.contains("#src/ose/OSECF")
        - file.tags.contains("#src/ose/OSEAF")
        - file.tags.contains("#src/ose/HB")
views:
  - type: list
    name: List
    order:
      - file.name

```

## **玩家自制/未经测试**

```base
filters:
  and:
    - file.tags.contains("#ose/class")
    - file.tags.contains("#src/ose/HB")
views:
  - type: list
    name: List
    order:
      - file.name

```
%%

# **法术**

## 牧师法术

```base
filters:
  and:
    - file.tags.contains("#ose/spell")
    - '!file.path.contains("_template")'
    - 'file.properties["cleric-spell-level"] >= 1'
properties:
  cleric-spell-level:
    displayName: 环位
  file.name:
    displayName: 法术
views:
  - type: table
    name: Table
    groupBy:
      property: cleric-spell-level
      direction: ASC
    order:
      - cleric-spell-level
      - file.name
```


## 魔法师法术

```base
filters:
  and:
    - file.tags.contains("#ose/spell")
    - '!file.path.contains("_template")'
    - 'file.properties["magic-user-spell-level"] >= 1'
properties:
  magic-user-spell-level:
    displayName: 环位
  file.name:
    displayName: 法术
views:
  - type: table
    name: Table
    groupBy:
      property: magic-user-spell-level
      direction: ASC
    order:
      - magic-user-spell-level
      - file.name
```

## 德鲁伊法术

```base
filters:
  and:
    - file.tags.contains("#ose/spell")
    - '!file.path.contains("_template")'
    - 'file.properties["druid-spell-level"] >= 1'
properties:
  druid-spell-level:
    displayName: 环位
  file.name:
    displayName: 法术
views:
  - type: table
    name: Table
    groupBy:
      property: druid-spell-level
      direction: ASC
    order:
      - druid-spell-level
      - file.name
```

## 幻术师法术

```base
filters:
  and:
    - file.tags.contains("#ose/spell")
    - '!file.path.contains("_template")'
    - 'file.properties["illusionist-spell-level"] >= 1'
properties:
  illusionist-spell-level:
    displayName: 环位
  file.name:
    displayName: 法术
views:
  - type: table
    name: Table
    groupBy:
      property: illusionist-spell-level
      direction: ASC
    order:
      - illusionist-spell-level
      - file.name
```

## 其他

```base
filters:
  and:
    - file.tags.contains("#ose/spell/list")
views:
  - type: list
    name: List
```

[^2]: 高等奇幻允许种族和职业分离。我不使用这条可选规则，故不收录种族。
