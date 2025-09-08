
# Make LVGL
cmake_minimum_required(VERSION 3.12.4)
project(TestLVGL C)

#set(CONFIG_LV_BUILD_EXAMPLES OFF)
set(CONFIG_LV_BUILD_DEMOS OFF CACHE BOOL "Disable LVGL examples" FORCE)
set(CONFIG_LV_BUILD_EXAMPLES OFF CACHE BOOL "Disable LVGL examples" FORCE)
set(LV_BUILD_CONF_PATH "${CMAKE_CURRENT_SOURCE_DIR}/lv_conf.h")

add_subdirectory(lvgl) 

