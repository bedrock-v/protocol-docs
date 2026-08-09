# SetActorLinkPacket

`packet` - id **41**

Sent when the player starts riding something. Two are sent at a time for some reason.

```mermaid
flowchart LR
  ROOT(["SetActorLinkPacket"])
  ROOT -->|"Link"| ActorLink["ActorLink"]
```

