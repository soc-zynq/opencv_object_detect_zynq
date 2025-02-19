# Create a library called "opencv_object_detect_zynq"
add_library(opencv_object_detect_zynq_lib opencv_object_detect_zynq.cpp)

# Specify include directories for the library
target_include_directories(opencv_object_detect_zynq_lib PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../../include)
