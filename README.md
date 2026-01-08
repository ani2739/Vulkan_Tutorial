**Vulkan Tutorial 🚀**

A step-by-step journey into modern low-level graphics programming using Vulkan

📌 Overview

This repository is a hands-on Vulkan tutorial designed to help developers understand Vulkan from fundamentals to practical rendering concepts.
It focuses on clarity, correctness, and real-world graphics programming practices, making it suitable for both beginners and experienced engineers transitioning to Vulkan.

Vulkan is a low-level, explicit, cross-platform graphics and compute API that provides high performance and fine-grained control over GPU resources. This tutorial breaks down Vulkan’s complexity into small, understandable steps.

Before starting this journey we need to create setup

**Linux**

Run the following command to install dependencies on Linux:
./scripts/install_dependencies_linux.sh

This script detects your package manager (apt, dnf, pacman) and installs the required dependencies, including: * Build essentials (gcc, cmake, ninja-build) * GLFW, GLM, tinyobjloader, stb * X Window System dependencies
It also provides instructions for installing the Vulkan SDK.

**Windows**

Run the following command to install dependencies on Windows:
scripts\install_dependencies_windows.bat

This script uses vcpkg to install the required dependencies, including: * GLFW, GLM, tinyobjloader, stb
You will also need to install the Vulkan SDK separately from https://vulkan.lunarg.com/.
