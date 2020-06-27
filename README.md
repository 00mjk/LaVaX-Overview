# DeViX (Overview)

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

Vulkan API wrapper of DirectX 12 Ultimate (but uses DXIL instead of SPIR-V)

<img src="https://cdn.wccftech.com/wp-content/uploads/2015/03/Vulkan-API-31.jpg" width="400" alt="DXVulkan"/>

You can participate to beta, development, or just do donation, you can [here](https://github.com/helixd2s/Overview)... 


### Why is need?

- DirectX 12 Ultimate more optimized for games
- Modern GPU support mostly for DirectX 12 Ultimate
- Most features of GPU's implemented mostly for DirectX 12 Ultimate
- Graphics development on UWP limited on DirectX 12 Ultimate only
- Khronos Group not planned to support Vulkan API on the Windows Platforms
- DirectX 12 has developer port for Windows 7 (but, WILL NO support for that) 
- Writing for both API are hard task for developers...


### Limitations

- Shader modules accept only DXIL intermediate code, so you can use only HLSL
- Every binding ID of all descriptor sets should to be unique per every pipeline (but can to be array)
- This wrapper are similar D3D12 for Windows 7 (i.e. only for developers)
- Support only for Windows 10 Build 2004 or beyond, and WSL-2 with WDDM v2.9
- Support only as Visual Studio 2019 Project, there is NO CMAKE... it made for precise control, for single DLL library
- It DOES NOT replace the regular Vulkan API in full, but is as similar as possible, which provides portability
- Required Windows 10 SDK (10.0.19041.0 or higher) for compile that project
- For maximal semantics, will **require** some extensions for correct usage 
- Vulkan API version will always forced as `1.2.145` (or beyond) and...
- Always **require** `VK_EXT_extended_dynamic_state` extension


### Stages

- Development
- Alpha testing
- Closed beta testing (for patrons)
- Open beta testing (for patrons, by invite)
- Public release (will placed on our the website)
- Beta of next release (for patrons, by invite)


### Bug Reporting

- I will not accept any issue without test code or donation (for write by myself)
- I can accept you as developer members by 5$ (if you get interest me) or 10$ contribution


### Pull Request

I will accept only myself reviewed pull requests... 
