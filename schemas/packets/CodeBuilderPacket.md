# CodeBuilderPacket

`packet` - id **150**

This is EDU exclusively.It is sent once from _sendLevelData() in the start of a game from the server,
	and once per CodeBuilderCommand

```mermaid
flowchart LR
  ROOT(["CodeBuilderPacket"])
  ROOT -->|"URL"| string["string"]
  ROOT -->|"Should open code builder"| boolean["boolean"]
```

