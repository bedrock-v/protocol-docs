# UpdateBlockSyncedPacket

`packet` - id **110**

Variation of UpdateBlockSyncedPacket that includes information to sync entities with renderchunk generation. Occasionally when blocks change a sync message is sent and during the change on the dimension, this packet is sent to the client to alert the update flags and sync info at a specific position.

```mermaid
flowchart LR
  ROOT(["UpdateBlockSyncedPacket"])
  ROOT -->|"Block Position"| BlockPos["BlockPos"]
  ROOT -->|"Block Runtime ID"| uint32["uint32"]
  ROOT -->|"Flags"| uint32["uint32"]
  ROOT -->|"Layer"| uint32["uint32"]
  ROOT -->|"Unique Actor Id"| uint64["uint64"]
  ROOT -->|"Actor Sync Message"| uint64["uint64"]
```

