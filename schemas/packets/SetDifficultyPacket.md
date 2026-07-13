# SetDifficultyPacket

`packet` - id **60**

- protocol: 2168
- minecraft: 1.26.40

Used for when a client changes difficulty through the menu or when the server changes the difficulty.

```mermaid
flowchart LR
  ROOT(["SetDifficultyPacket"])
  ROOT -->|"Difficulty"| uint32["uint32"]
```

