cmake_minimum_required(VERSION 3.20)

project(vulkan_layer)

add_subdirectory(SPIRV-Headers)
add_subdirectory(hip_dummy)
add_subdirectory(cpp_helper)
add_subdirectory(constexpr_map)
add_subdirectory(win32_helper)
add_subdirectory(map_file)
add_subdirectory(spirv_parser)
add_subdirectory(Vulkan-Headers)
set(vulkan_registry_xml ${CMAKE_CURRENT_SOURCE_DIR}/Vulkan-Headers/registry/vk.xml)
add_subdirectory(vulkan_layer)
