# Overview

**This repository is for testing CUDA C/C++ code for high-performance, GPU-Accelerated, parallel computing on Nvidia GeForce GPU's**

Current Hardware: `Nvidia GeForce RTX 4080 Super 16GB 2550 MHz`

## Getting Started with Nvidia CUDA

1. Download the CUDA Toolkit 12.6 from [Download CUDA](https://developer.nvidia.com/cuda-downloads)

2. Select Windows > x86_64 > 11 > exe (local) > Click "Download (3.0 GB)" button

3. Follow on-screen prompts through the installation process. Select the default settings on everything until the "Options" menu.

4. **IMPORTANT:** Under "Options" select "Custom (Advanced)" installation option. Uncheck anything that tries to install an old driver than the one you alreadyy have (such as Display Driver). You may also deselect any component that is already installed at the same "Current Version" as the "New Version" that it shows in the window.

![CUDA Installer Screenshot 1](https://github.com/user-attachments/assets/c3ed557b-8634-41f6-b666-3d15b99f7ac9)

![CUDA Installer Screenshot 2](https://github.com/user-attachments/assets/aeeb40b0-435b-4361-9ede-cebe5a2000f1)

5. Upon completing the installation, you now should have the CUDA Toolkit installed on your computer and you can now run CUDA applications such as this one in Visual Studio. (Note: Intellisense in Visual Studio may show error(s) where there are none. Simply build the project and see if it runs)
