cmake_minimum_required(VERSION 3.20)

project(vulkan_layer)

add_subdirectory(SPIRV-Headers)
add_subdirectory(hip_dummy)
add_subdirectory(cpp_helper)
#add_subdirectory(win32_helper)
add_subdirectory(constexpr_map)
add_subdirectory(SPIRV-Parser)
add_subdirectory(vulkan_layer)
