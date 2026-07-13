# server_config

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["server_config"])
  ROOT -->|"gathering"| gatheringsConfig["gatheringsConfig"]
  ROOT -->|"clientStoreEntryPoint"| clientStoreEntryPointConfig["clientStoreEntryPointConfig"]
  ROOT -->|"presence"| presenceConfig["presenceConfig"]
```

