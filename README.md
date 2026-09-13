# Fjell — Releases

Prebuilt downloads for the [Fjell](https://github.com/thomppa030/Fjell) engine.
This repository holds no source; it exists so builds can be downloaded without
a GitHub account.

## Downloads

Grab the latest build from the [Releases](../../releases) page:

| | |
|---|---|
| `Fjell-<version>-win64.zip` | Windows 10/11, x64 |
| `Fjell-<version>-Linux.tar.gz` | Linux, x64 |

Unpack anywhere and run `fjell-hub` to create or open a project.

## Prerequisites

The [Vulkan SDK](https://vulkan.lunarg.com/) is required. The engine compiles
material shaders as it loads them, so it needs the SDK's `glslc` at runtime,
not just to build.

Writing gameplay scripts additionally needs a C++23 compiler — MSVC 2022 on
Windows, GCC 13+ or Clang 17+ on Linux — along with CMake 4.3+ and Ninja. The
editor invokes them for you; it does not ship them.
