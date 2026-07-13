# SubChunkHeightmapData

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["SubChunkHeightmapData"])
  ROOT -->|"Height Map Type"| uint8["uint8"]
  ROOT -->|"Subchunk Height Map"| int8["int8[][]"]
  ROOT -->|"Render Height Map Type"| uint8["uint8"]
  ROOT -->|"Subchunk Render Height Map"| int8["int8[][]"]
```

