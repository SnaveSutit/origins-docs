---
title: Modify Damage Taken (Power Type)
date: 2021-04-06
---
# Modify Damage Taken

[Power Type](../power_types.md).

Modifies how much melee damage the player deals.

Type ID: `origins:modify_damage_taken`

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`damage_condition` | [Damage Condition](../damage_conditions.md) | _optional_ | If set, the modifiers will only apply to damage which satisfies this condition.
`modifier` | [Attribute Modifier](../data_types/attribute_modifier.md) | _optional_ | If set, this modifier will apply to the damage amount.
`modifiers` | [Array](../data_types/array.md) of [Attribute Modifiers](../data_types/attribute_modifier.md) | _optional_ | If set, these modifiers will apply to the damage amount.