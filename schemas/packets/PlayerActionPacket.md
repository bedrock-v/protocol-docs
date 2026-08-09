# PlayerActionPacket

`packet` - id **36**

The expected actions change depending on the ServerAuthMovementMode specified in the StartGamePacket.
	See the PlayerActionType enum for details on which have differing behavior.
	See also PlayerAuthInputPacket and InventoryTransactionPacket for similar types of player actions.

```mermaid
flowchart LR
  ROOT(["PlayerActionPacket"])
  ROOT -->|"Player Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Action"| PlayerActionType["PlayerActionType"]
  ROOT -->|"Block Position"| BlockPos["BlockPos"]
  ROOT -->|"Result Pos"| BlockPos["BlockPos"]
  ROOT -->|"Face"| int32["int32"]
```

