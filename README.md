# VkTDSE
VkTDSEs (Vulkan Time-Dependent Schrödinger Equation) is a GPU-accelerated solver for the Time-Dependent Schrödinger Equation in 2D, implemented with Vulkan compute shaders. It simulates the evolution of Gaussian wave packets in configurable 2D potential landscapes with real-time visualization.

## Dependencies
- [Vulkan SDK](https://vulkan.lunarg.com/)
- [GLFW](https://www.glfw.org/)
- [Vulkan Memory Allocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator)
- [CMake](https://cmake.org/download/)

## Installation
```zsh
mkdir build && cd build
cmake ..
make -jN
```
where N is the number of system threads.

## Usage
```zsh
./VkTDSE <config>
```
| Config | Description         |
| :----- | :------------------ |
| 0      | Free particle       |
| 1      | Potential barrier   |
| 2      | Double slit barrier |

## Documentation
- [Project Report](docs/PHYS1321_FinalProject.pdf)
- [Presentation Slides](docs/PHYS1321_FinalProject_Slides.pdf)

## License
[MIT](https://choosealicense.com/licenses/mit/)
