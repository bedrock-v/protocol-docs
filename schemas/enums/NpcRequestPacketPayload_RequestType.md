# NpcRequestPacketPayload RequestType

`enum` - wire `uint8`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart TB
  ROOT(["NpcRequestPacketPayload RequestType"])
  ROOT --> SetActions["SetActions"]
  ROOT --> ExecuteAction["ExecuteAction"]
  ROOT --> ExecuteClosingCommands["ExecuteClosingCommands"]
  ROOT --> SetName["SetName"]
  ROOT --> SetSkin["SetSkin"]
  ROOT --> SetInteractText["SetInteractText"]
  ROOT --> ExecuteOpeningCommands["ExecuteOpeningCommands"]
```

