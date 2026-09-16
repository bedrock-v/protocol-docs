# ClientboundUpdateSoundDataPacket

`packet` - id **348**



```mermaid
flowchart LR
  ROOT(["ClientboundUpdateSoundDataPacket"])
  ROOT -->|"Server Sound Handle"| ServerSoundHandle["ServerSoundHandle"]
  ROOT -->|"Event"| Stop___SetVolume___SetPitch___Fade___SeekTo___Pause___Resume["Stop | SetVolume | SetPitch | Fade | SeekTo | Pause | Resume"]
```

