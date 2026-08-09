# UpdateClientInputLocksPacket

`packet` - id **196**

Used to update the players input permissions. Sends the full permission set and the server position of the player at the time the permission was modified.

```mermaid
flowchart LR
  ROOT(["UpdateClientInputLocksPacket"])
  ROOT -->|"Input Lock ComponentData"| uint32["uint32"]
```

