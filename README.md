# AtlasWeave Engine
 
**AtlasWeave Engine** is a hobby project designed to explore 3D rendering and game engine architecture in C#.  
The engine uses **Vulkan** for low-level graphics control and **Silk.NET** for cross-platform support.  
It features a modular structure with an **ECS-based architecture** and optional **2D overlay** for UI or simple 2D games.
 
The goal of this project is to **learn and experiment** with modern rendering techniques, multi-threaded engine design, and scalable game logic — rather than building a production-ready engine.
 
## Features
- Vulkan-based 3D renderer for learning graphics programming
- Modular **Entity Component System (ECS)**
- Multi-threaded architecture for CPU performance exploration
- Optional 2D overlay for HUDs, UI, or 2D experiments
- Simple terrain and mesh rendering
- Debug tools for profiling and learning engine internals
 
## Roadmap
- **Phase 1:** Core engine setup, windowing, input
- **Phase 2:** Vulkan initialization, swapchain, command buffers
- **Phase 3:** ECS and basic 3D rendering
- **Phase 4:** Terrain streaming, camera, 2D overlay
- **Phase 5:** Debug tools, simple physics, optional 2D sprite rendering
 
## Getting Started
Clone the repository and open the solution in Visual Studio or JetBrains Rider.  
Make sure to install the Vulkan SDK and Silk.NET dependencies to build and run the engine.
 
```bash
git clone https://github.com/olafrose/AtlasWeave.git

```

 ## Dependencies
 Vulkan SDK v1.4.328.1
 Silk.NET v2.22.0
- Silk.NET.Windowing
- Silk.NET.Vulkan
