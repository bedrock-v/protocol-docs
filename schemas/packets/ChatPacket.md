# ChatPacket

`packet` - id **361**

Carries a Chat Service signature that receiving clients verify. The hosting server relays the signed block unmodified, may decorate around it, and chooses the room it goes to.

```mermaid
flowchart LR
  ROOT(["ChatPacket"])
  ROOT -->|"Signed Chat"| SignedChat["SignedChat"]
  ROOT -->|"Room Id"| string["string"]
  ROOT -->|"Formatting"| ChatFormatting["ChatFormatting"]
```

