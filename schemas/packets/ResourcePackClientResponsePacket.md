# ResourcePackClientResponsePacket

`packet` - id **8**

Sent to MinecraftGame to complete the resource pack loading process.

```mermaid
flowchart LR
  ROOT(["ResourcePackClientResponsePacket"])
  ROOT -->|"Response"| Resource_Pack_Client_Response___Cancel___Resource_Pack_Client_Response___Downloading___Resource_Pack_Client_Response___Downloading_Finished___Resource_Pack_Client_Response___Resource_Pack_Stack_Finished["Resource_Pack_Client_Response_-_Cancel | Resource_Pack_Client_Response_-_Downloading | Resource_Pack_Client_Response_-_Downloading_Finished | Resource_Pack_Client_Response_-_Resource_Pack_Stack_Finished"]
```

