# Buoy Works

### Directory
```
buoy-works/
├── buoy/                         # Main engine core
│   ├── include/buoy/             # Public API definitions (Headers)
│   │   └── port/                 # Target environment & event pipeline definitions
│   └── src/buoy/                 # Public API implementations (Source)
│       ├── port/                 # Platform-specific & event pipeline implementations
│       ├── components/           # ECS Components (Actual data management)
│       ├── geometries/           # Geometry implementations
│       ├── materials/            # Material implementations
│       └── ...                   # etc.
├── external/                     # 3rd-party library dependencies
│   ├── glm/                      # OpenGL Mathematics (sub-module)
│   ├── filament/                 # PBR rendering engine (sub-module)
│   └── ...                       # etc.
├── docs/                         # Documentation and guides
│   ├── images/                   # Diagrams and screenshots for documentation
│   └── ...                       # etc.
├── samples/                      # Example projects and usage demos
│   └── assets/                   # Resources for samples
│       ├── glTF-Sample-Models/   # 3D models (sub-module)
│       ├── textures/             # Texture images
│       └── ...                   # etc.
├── build/                        # Build configurations and toolchains (.gitignore)
└── out/                          # Build output directory (.gitignore)
```
