cmake_minimum_required(VERSION 3.20)
project(TubesPMC)

set(nappgui_DIR ./nappgui/cmake)
find_package(nappgui REQUIRED)
include("${NAPPGUI_ROOT_PATH}/prj/NAppCompilers.cmake")
nap_config_compiler()
include("${NAPPGUI_ROOT_PATH}/prj/NAppProject.cmake")
nap_project_desktop_app(KlinikX klinikx)