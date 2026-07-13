# ShowProfilePacket

`packet` - id **104**

- protocol: 2168
- minecraft: 1.26.40

The only use in vanilla is a test command called ProfileCommand. It makes the user's xbox profile popup.

```mermaid
flowchart LR
  ROOT(["ShowProfilePacket"])
  ROOT -->|"Player XUID"| string["string"]
```

