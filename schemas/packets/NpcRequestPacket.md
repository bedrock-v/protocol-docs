# NpcRequestPacket

`packet` - id **98**

A request is made from the client during an interaction with an NPC then the request is processed by the server. 
	Actor MUST have the NPCComponent to be handled. 
	We currently only use this for EDU, but the goal was to expose the NPC Component to creators.

```mermaid
flowchart LR
  ROOT(["NpcRequestPacket"])
  ROOT -->|"NPC Runtime ID"| ActorRuntimeID["ActorRuntimeID"]
  ROOT -->|"Request Type"| NpcRequestPacketPayload_RequestType["NpcRequestPacketPayload_RequestType"]
  ROOT -->|"Actions"| string["string"]
  ROOT -->|"Action Index"| uint8["uint8"]
  ROOT -->|"Scene Name"| string["string"]
```

