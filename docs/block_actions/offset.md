---
title: Offset (Action)
date: 2021-04-05
---
# Offset

[Block Action](../block_actions.md).

A meta-action which instead applies the provided [Block Action](../block_actions.md) at a position offset from the current position.

Type ID: `origins:offset`

### Fields

Field  | Type | Default | Description
-------|------|---------|-------------
`action` | [Block Action](../block_actions.md) | | The action to apply with the given offset.
`x` | [Integer](../data_types/integer.md) | `0` | How much to offset the position on the x-axis.
`y` | [Integer](../data_types/integer.md) | `0` | How much to offset the position on the y-axis.
`z` | [Integer](../data_types/integer.md) | `0` | How much to offset the position on the z-axis.