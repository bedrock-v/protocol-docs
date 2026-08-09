# CreativeContentPacket

`packet` - id **145**

Sent once by the server on startup to tell clients all of the items that can show up in the creative menu and recipe book.

```mermaid
flowchart LR
  ROOT(["CreativeContentPacket"])
  ROOT -->|"Groups"| CreativeGroupInfoPayload["CreativeGroupInfoPayload[]"]
  ROOT -->|"Entries"| CreativeItemEntryPayload["CreativeItemEntryPayload[]"]
```

