# SubChunkPacketPayload::SubChunkRequestResult

`enum` - wire `uint8`

```mermaid
flowchart TB
  ROOT(["SubChunkPacketPayload::SubChunkRequestResult"])
  ROOT --> Undefined["Undefined"]
  ROOT --> Success["Success"]
  ROOT --> LevelChunkDoesntExist["LevelChunkDoesntExist"]
  ROOT --> WrongDimension["WrongDimension"]
  ROOT --> PlayerDoesntExist["PlayerDoesntExist"]
  ROOT --> IndexOutOfBounds["IndexOutOfBounds"]
  ROOT --> SuccessAllAir["SuccessAllAir"]
```

