# AFE-PC-Port

A native PC port of **Animal Forest e+ (Dōbutsu no Mori e+)** for Nintendo GameCube, utilizing modern hardware APIs and a cleanroom architecture approach.

## ⚠️ Disclaimer
* This repository contains **only source code, build scripts, and platform adaptation layers**. 
* **No copyrighted assets, ROMs, audio, textures, or proprietary Nintendo binaries are hosted here.**
* To build and run this port, you must legally dump your own copy of the *Animal Forest e+* (Japan) ISO (`GAEJ01`) for runtime asset extraction.

## 🙏 Credits & Acknowledgments
* **[ACreTeam (afe-decomp)](https://github.com/ACreTeam/afe-decomp):** Massive thanks to the ACreTeam for their foundational work on the game's decompilation and reverse engineering efforts. This port builds upon the structural insights provided by their research.
* **Community Contributors:** Everyone helping map out memory addresses, rendering pipelines, and game logic.

## Requirements
- CMake 3.20+
- A modern C++ compiler (GCC, Clang, or MSVC)
- SDL2 (for window creation, input, and audio)
- A legally obtained `GAEJ01` ROM for asset extraction.

## Building from Source
1. Clone the repository:
   ```bash
   git clone [https://github.com/luispolis124/afe-pc-port.git](https://github.com/luispolis124/afe-pc-port.git)
   cd afe-pc-port

```
 2. Create a build directory and compile:
   ```bash
   mkdir build && cd build
   cmake ..
   cmake --build .
   
   ```
 3. Place your dumped GAEJ01 ISO or extracted files into the designated data directory before running the executable.
