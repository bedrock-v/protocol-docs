# SubChunkPacket

`packet` - id **174**

Contains subchunk terrain data, heightmaps, and optional blob cache IDs.

```mermaid
flowchart LR
  ROOT(["SubChunkPacket"])
  ROOT -->|"Cache Enabled"| boolean["boolean"]
  ROOT -->|"Dimension Type"| DimensionType["DimensionType"]
  ROOT -->|"Center Pos"| SubChunkPos["SubChunkPos"]
  ROOT -->|"SubChunk Data"| SubChunkPacketData["SubChunkPacketData[]"]
```

