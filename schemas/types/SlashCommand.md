# SlashCommand

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["SlashCommand"])
  ROOT -->|"Success Count"| int32["int32"]
  ROOT -->|"Error Count"| int32["int32"]
  ROOT -->|"Command Name"| string["string"]
  ROOT -->|"Error List"| string["string"]
```

