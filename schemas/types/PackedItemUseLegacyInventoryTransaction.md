# PackedItemUseLegacyInventoryTransaction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["PackedItemUseLegacyInventoryTransaction"])
  ROOT -->|"Legacy Request ID"| ItemStackLegacyRequestId["ItemStackLegacyRequestId"]
  ROOT -->|"Legacy Set Item Slots"| LegacySetSlot["LegacySetSlot[]"]
  ROOT -->|"Item Use Transaction"| ItemUseInventoryTransaction["ItemUseInventoryTransaction"]
```

