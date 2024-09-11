# Vulkan Template Project

## About

Personal Vulkan Template based on my sample base class, but with several changes, optimizations, etc.

**Note:** Not guaranteed to work

Uses
- glm
- ktx
- imgui
- tinygltf
- volk
- dxc
- tracy
- sfml

Functionality
- dynamic rendering
- hlsl shaders
- hot reload for shaders and assets

## Build (MacOS)
Tested on M3 Macbook Pro
```
mkdir build
cd build
cmake -G "Ninja" -D CMAKE_CXX_COMPILER=clang++ -D CMAKE_C_COMPILER=clang ..
cmake --build .
```
