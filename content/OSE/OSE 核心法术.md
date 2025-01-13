---
title: OSE 核心法术
date: 2025-01-10
tags:
  - ose/list/spell
author:
  - 整理 & 修改/狷墨居主人
titlepage: true
toc: true
toc-title: 目录
toc-own-page: true
---

# OSE 经典奇幻 & 高等奇幻

## 牧师法术

<!-- QueryToSerialize: Table without id cleric-spell-level as 环位, rows.file.link as 法术 from #src/ose/OSECF and #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template") group by cleric-spell-level -->
<!-- SerializedQuery: Table without id cleric-spell-level as 环位, rows.file.link as 法术 from #src/ose/OSECF and #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template") group by cleric-spell-level -->

| 环位 | 法术                                                                                                                                                                                                                                                                                                                                    |
| -- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | <ul><li>[[防护邪恶]]</li><li>[[移除恐惧]]</li><li>[[抵抗寒冷]]</li><li>[[净化饮食]]</li><li>[[侦测邪恶]]</li><li>[[治愈轻伤]]</li><li>[[光亮]]</li><li>[[侦测魔法]]</li></ul>         |
| 2  | <ul><li>[[魅惑蛇类]]</li><li>[[祝福]]</li><li>[[知晓阵营]]</li><li>[[沉默 15'半径]]</li><li>[[抵抗火焰]]</li><li>[[寻找陷阱]]</li><li>[[定身类人]]</li><li>[[动物交谈]]</li></ul> |
| 3  | <ul><li>[[移除诅咒]]</li><li>[[治愈疾病]]</li><li>[[恒久光亮]]</li><li>[[强击]]</li><li>[[定位物体]]</li><li>[[动物生长]]</li></ul>                                                                                       |
| 4  | <ul><li>[[防护邪恶 10'半径]]</li><li>[[化杖为蛇]]</li><li>[[中和毒素]]</li><li>[[造水]]</li><li>[[治愈重伤]]</li><li>[[植物交谈]]</li></ul>                                                                           |
| 5  | <ul><li>[[驱散邪恶]]</li><li>[[通神]]</li><li>[[虫灾]]</li><li>[[复活死者]]</li><li>[[创造食物]]</li><li>[[使命]]</li></ul>                                                                                               |
<!-- SerializedQuery END -->



%%
```dataview
Table without id cleric-spell-level as 环位, rows.file.link as 法术 from #src/ose/OSECF and #ose/spell where cleric-spell-level >= 1 and !contains(file.path, "_template") group by cleric-spell-level
``` 
%%

## 魔法师法术
 
<!-- QueryToSerialize: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #src/ose/OSECF and #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->
<!-- SerializedQuery: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #src/ose/OSECF and #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->

| 环位 | 法术                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| -- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | <ul><li>[[魔法飞弹]]</li><li>[[魅惑类人]]</li><li>[[防护邪恶]]</li><li>[[解读文书]]</li><li>[[睡眠]]</li><li>[[浮空碟]]</li><li>[[护盾]]</li><li>[[封门]]</li><li>[[光亮]]</li><li>[[阅读魔法]]</li><li>[[侦测魔法]]</li><li>[[魔嘴]]</li></ul>         |
| 2  | <ul><li>[[超感]]</li><li>[[蛛网]]</li><li>[[漂浮]]</li><li>[[法师之锁]]</li><li>[[敲击]]</li><li>[[恒久光亮]]</li><li>[[定位物体]]</li><li>[[侦测隐形]]</li><li>[[侦测邪恶]]</li><li>[[虚幻之力]]</li><li>[[隐形]]</li><li>[[镜影]]</li></ul>           |
| 3  | <ul><li>[[飞行]]</li><li>[[隐形 10' 半径]]</li><li>[[防护邪恶 10'半径]]</li><li>[[防护普通投射物]]</li><li>[[闪电束]]</li><li>[[视觉共感]]</li><li>[[红外视觉]]</li><li>[[火球]]</li><li>[[加速]]</li><li>[[水中呼吸]]</li><li>[[驱散魔法]]</li></ul>            |
| 4  | <ul><li>[[魅惑怪物]]</li><li>[[移除诅咒]]</li><li>[[火墙]]</li><li>[[法师之眼]]</li><li>[[次元门]]</li><li>[[植物生长]]</li><li>[[幻景]]</li><li>[[幻化林木]]</li><li>[[困惑]]</li><li>[[变形自我]]</li><li>[[变形他人]]</li><li>[[冰墙]]</li></ul>     |
| 5  | <ul><li>[[魔魂壶]]</li><li>[[穿墙]]</li><li>[[石墙]]</li><li>[[活化尸体]]</li><li>[[杀戮之云]]</li><li>[[探知高层位面]]</li><li>[[心灵遥控]]</li><li>[[弱智]]</li><li>[[定身类人]]</li><li>[[咒唤元素]]</li><li>[[传送]]</li><li>[[化石为泥]]</li></ul> |
| 6  | <ul><li>[[隐形潜伏怪]]</li><li>[[降低水位]]</li><li>[[转生]]</li><li>[[解离]]</li><li>[[移土]]</li><li>[[死亡法咒]]</li><li>[[指使]]</li><li>[[投影]]</li><li>[[反魔罩]]</li><li>[[化石为肉]]</li><li>[[分水]]</li><li>[[操纵天气]]</li></ul>           |
<!-- SerializedQuery END -->

## 德鲁伊法术

<!-- QueryToSerialize: Table without id druid-spell-level as 环位, rows.file.link as 法术 from (#src/ose/OSEAF or #src/ose/OSECF) and #ose/spell where druid-spell-level >= 1 and !contains(file.path, "_template") group by druid-spell-level -->
<!-- SerializedQuery: Table without id druid-spell-level as 环位, rows.file.link as 法术 from (#src/ose/OSEAF or #src/ose/OSECF) and #ose/spell where druid-spell-level >= 1 and !contains(file.path, "_template") group by druid-spell-level -->

| 环位 | 法术                                                                                                                                                                                                                                                                                                                                |
| -- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | <ul><li>[[动物交谈]]</li><li>[[侦测危险]]</li><li>[[化兽为友]]</li><li>[[妖火]]</li><li>[[预测天气]]</li><li>[[纠缠术]]</li><li>[[定位植物或动物]]</li><li>[[动物无视]]</li></ul> |
| 2  | <ul><li>[[造水]]</li><li>[[治愈轻伤]]</li><li>[[减缓毒发]]</li><li>[[炙热金属]]</li><li>[[燃火]]</li><li>[[隐雾]]</li><li>[[曲木]]</li><li>[[树肤]]</li></ul>                     |
| 3  | <ul><li>[[水中呼吸]]</li><li>[[树木形态]]</li><li>[[自然生长]]</li><li>[[防护毒素]]</li><li>[[定身动物]]</li><li>[[召雷]]</li></ul>                                                                                   |
| 4  | <ul><li>[[治愈重伤]]</li><li>[[驱散魔法]]</li><li>[[植物交谈]]</li><li>[[召唤动物]]</li><li>[[温度控制]]</li><li>[[防护火焰与闪电]]</li></ul>                                                                         |
| 5  | <ul><li>[[操纵天气]]</li><li>[[化石为泥]]</li><li>[[树木穿行]]</li><li>[[沟通自然]]</li><li>[[荆棘之墙]]</li><li>[[防护植物与动物]]</li></ul>                                                                         |
<!-- SerializedQuery END -->

# Carcass Crawler

## 魔法师法术

<!-- QueryToSerialize: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #src/ose/CC  and #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->
<!-- SerializedQuery: Table without id magic-user-spell-level as 环位, rows.file.link as 法术 from #src/ose/CC  and #ose/spell where magic-user-spell-level >= 1 and !contains(file.path, "_template") group by magic-user-spell-level -->

| 环位 | 法术                                                                                                                                                        |
| -- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1  | <ul><li>[[燃烧之手]]</li><li>[[电爪]]</li><li>[[羽落]]</li><li>[[隐形仆役]]</li></ul> |
| 2  | <ul><li>[[衰弱射线]]</li><li>[[烟火]]</li><li>[[臭云]]</li></ul>                                       |
| 3  | <ul><li>[[通晓语言]]</li><li>[[闪现]]</li><li>[[缓慢]]</li></ul>                                       |
<!-- SerializedQuery END -->
