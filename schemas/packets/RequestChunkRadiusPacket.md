# RequestChunkRadiusPacket

`packet` - id **69**

This packet is to make sure that the server expands/shrinks first. Additionally for ClientSide Chunk Generation we can send a byte, based on client's hardware capabilities what is the max chunk radius client can handle.

```mermaid
flowchart LR
  ROOT(["RequestChunkRadiusPacket"])
  ROOT -->|"Chunk Radius"| int32["int32"]
  ROOT -->|"Max ChunkRadius"| uint8["uint8"]
```

