# JigsawStructureDataPacket

`packet` - id **313**

- protocol: 2168
- minecraft: 1.26.40

Sends the serialized jigsaw rule JSON to the client as it's needed on both the client and server.

```mermaid
flowchart LR
  ROOT(["JigsawStructureDataPacket"])
  ROOT -->|"Jigsaw Structure Data Tag"| unknown["unknown"]
```

