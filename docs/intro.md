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
    enchant: razor # 附魔ID，请使用小写
    level: 2 # 附魔等级
  ...其他配置 (如 触发器, 筛选器, 目标器, 等等)
```

> 别跟我说你要给防具增加此效果
> 这样做是不行的，这个效果只能用在武器上

## add_global_points

`注意:这是永久的效果`

当这个效果 **触发** 时，会给物品 **添加附魔**

```json
- id: add_enchant
  args:
    type: g_souls # 增加或减少的积分
    amount: 1 # 增加或减少的数值
  ...其他配置 (如 触发器, 筛选器, 目标器, 等等)
```

> 别跟我说你要给防具增加此效果
> 这样做是不行的，这个效果只能用在武器上





