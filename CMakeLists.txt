cmake_minimum_required(VERSION 3.0)
project(color_stud VERSION 0.1.0 LANGUAGES C CXX)
set(CMAKE_CXX_STANDARD 17)

file(GLOB src_files
    "src/*.cpp"
)

add_executable(${PROJECT_NAME} ${src_files})