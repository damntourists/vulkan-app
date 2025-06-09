# vulkan-app
Basic Vulkan starter app

## Prerequisites
Follow dev environment instructions at https://vulkan-tutorial.com/Development_environment#page_Linux

### Ubuntu
#### Build requirements
```shell
sudo apt install vulkan-tools libvulkan-dev install vulkan-validationlayers-dev spirv-tools libglfw3-dev libglm-dev
```

#### Shader compiler (glslc) 
Download Google's [unofficial binaries](https://github.com/google/shaderc/blob/main/downloads.md) and copy `glslc` to your `/usr/local/bin` directory

#### Vulkan SDK
Download https://vulkan.lunarg.com/sdk/home#linux