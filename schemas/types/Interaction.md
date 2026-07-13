# Interaction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["Interaction"])
  ROOT -->|"Interacted Entity ID"| int64["int64"]
  ROOT -->|"Interaction Type"| MinecraftEventing__InteractionType["MinecraftEventing__InteractionType"]
  ROOT -->|"Interaction Actor Type"| int32["int32"]
  ROOT -->|"Interaction Actor Variant"| int32["int32"]
  ROOT -->|"Interaction Actor Color"| uint8["uint8"]
```

