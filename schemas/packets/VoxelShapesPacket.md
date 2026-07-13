# VoxelShapesPacket

`packet` - id **337**

- protocol: 2168
- minecraft: 1.26.40

Sends the serializable voxel shapes data to the client as it's needed on both the client and server. This packet should always be sent before StartGamePacket.

```mermaid
flowchart LR
  ROOT(["VoxelShapesPacket"])
  ROOT -->|"Shapes"| VoxelShapes__SerializableVoxelShape["VoxelShapes__SerializableVoxelShape[]"]
  ROOT -->|"Name Map"| object["object"]
  ROOT -->|"Custom Shape Count"| uint16["uint16"]
```

