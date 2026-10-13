inc_dir = include_directories('include')

libImGui_cpp = static_library(
  'libImGui_cpp',
  'src/imgui-c++-latest.cpp',
  include_directories: inc_dir, 
  cpp_args: [cpp_std,],
  dependencies: [fmt_dep, imgui_dep,]
  )

libImGui_cpp_dep = declare_dependency(
  link_with: libImGui_cpp,
  include_directories: inc_dir,
  )
