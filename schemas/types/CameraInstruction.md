# CameraInstruction

`struct`

- protocol: 2168
- minecraft: 1.26.40

```mermaid
flowchart LR
  ROOT(["CameraInstruction"])
  ROOT -->|"Set"| CameraInstruction__SetInstruction["CameraInstruction__SetInstruction"]
  ROOT -->|"Clear"| boolean["boolean"]
  ROOT -->|"Fade"| CameraInstruction__FadeInstruction["CameraInstruction__FadeInstruction"]
  ROOT -->|"Target"| CameraInstruction__TargetInstruction["CameraInstruction__TargetInstruction"]
  ROOT -->|"RemoveTarget"| boolean["boolean"]
  ROOT -->|"FieldOfView"| CameraInstruction__FovInstruction["CameraInstruction__FovInstruction"]
  ROOT -->|"Spline"| CameraInstruction__SplineInstruction["CameraInstruction__SplineInstruction"]
  ROOT -->|"AttachToEntity"| CameraInstruction__AttachToEntityInstruction["CameraInstruction__AttachToEntityInstruction"]
  ROOT -->|"DetachFromEntity"| boolean["boolean"]
```

