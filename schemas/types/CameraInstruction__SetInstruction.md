# CameraInstruction::SetInstruction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["CameraInstruction::SetInstruction"])
  ROOT -->|"preset"| uint32["uint32"]
  ROOT -->|"ease"| CameraInstruction__SetInstruction__EaseOption["CameraInstruction__SetInstruction__EaseOption"]
  ROOT -->|"pos"| CameraInstruction__SetInstruction__PosOption["CameraInstruction__SetInstruction__PosOption"]
  ROOT -->|"rot"| CameraInstruction__SetInstruction__RotOption["CameraInstruction__SetInstruction__RotOption"]
  ROOT -->|"facing"| CameraInstruction__SetInstruction__FacingOption["CameraInstruction__SetInstruction__FacingOption"]
  ROOT -->|"view_offset"| CameraInstruction__SetInstruction__ViewOffsetOption["CameraInstruction__SetInstruction__ViewOffsetOption"]
  ROOT -->|"entity_offset"| CameraInstruction__SetInstruction__EntityOffsetOption["CameraInstruction__SetInstruction__EntityOffsetOption"]
  ROOT -->|"default"| boolean["boolean"]
  ROOT -->|"removeIgnoreStartingValuesComponent"| boolean["boolean"]
```

