add_library(qtpromise INTERFACE)

cmake_policy(SET CMP0076 NEW)

target_include_directories(qtpromise INTERFACE include/ ./ src/)
