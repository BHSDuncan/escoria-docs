<!-- Auto-generated from JSON by GDScript docs maker. Do not edit this document directly. -->

# InventoryAddCommand

**Extends:** [ESCBaseCommand](../ESCBaseCommand) < [Node](../Node)

## Description

`inventory_add item`

Adds an item to the inventory.

**Parameters**

- *item*: Global ID of the `ESCItem` to add to the inventory

@ESC

## Method Descriptions

### configure

```gdscript
func configure() -> ESCCommandArgumentDescriptor
```

Return the descriptor of the arguments of this command

### run

```gdscript
func run(command_params: Array) -> int
```

Run the command