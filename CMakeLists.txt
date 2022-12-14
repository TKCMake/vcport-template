# 本项目构件所须的CMake最低版本号
cmake_minimum_required (VERSION 3.5)

# 配置项目信息
project(
    PT_PORT_NAME # 项目名，会被保存到 PROJECT_NAME 变量
    VERSION 0.1.7 # 项目版本号（库版本）
    LANGUAGES CXX # 项目开发语言
)

add_subdirectory(include)
add_subdirectory(src)