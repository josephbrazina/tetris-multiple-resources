# Mental Rotation Task Stimuli

GitHub-ready stimulus folder for the mental rotation experiment.

## Contents

- `stimuli/rotations/A` through `J`: 10 selected 10-cube figures
- `stimuli/mirrored/A` through `J`: corresponding mirrored figures
- Each figure contains rotation indices `0` through `14`
- Images are JPEG files

## Expected paths

Same trials:

```text
stimuli/rotations/A/A0.jpg
stimuli/rotations/A/A14.jpg
```

Different trials:

```text
stimuli/mirrored/A/A0_m.jpg
stimuli/mirrored/A/A14_m.jpg
```

The HTML task should be kept at the repository root. The `stimuli` folder should also be at the repository root:

```text
repository/
├── mental_rotation_task_v4.html
└── stimuli/
    ├── rotations/
    │   ├── A/
    │   └── ...
    └── mirrored/
        ├── A/
        └── ...
```

The task uses `rotationIndex` values 0–14 and does not assign unsupported degree values.
