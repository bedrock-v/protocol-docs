# AnvilDamagePacket

`packet` - id **141**

- protocol: 2168
- minecraft: 1.26.40


	Only used when Item Stack Net Manager is disabled on the server.
	Sends the position of the anvil that is requesting to be damaged from the client.
	

```mermaid
flowchart LR
  ROOT(["AnvilDamagePacket"])
  ROOT -->|"Block Position"| BlockPos["BlockPos"]
```

