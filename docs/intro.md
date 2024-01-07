---
sidebar_position: 1
---

# 所有效果

## add_damage

`注意:需要触发器`

当这个效果 **触发** 时，会增加 **攻击力**

```json
- id: add_damage
  args:
    damage: 2 # 攻击力数值（增加或减少）
  ...其他配置 (如 触发器, 筛选器, 目标器, 等等)
```

## add_enchant

`注意:需要触发器`

当这个效果 **触发** 时，会给物品 **添加附魔**

```json
- id: add_enchant
  args:
    enchant: razor # 附魔ID
    level: 2 # 附魔等级
  ...其他配置 (如 触发器, 筛选器, 目标器, 等等)
```







