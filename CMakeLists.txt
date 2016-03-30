
project(sunwait)


cmake_minimum_required(VERSION 2.8)
file(GLOB SUNWAIT_SRC *.h *.c)

add_executable(sunwait ${SUNWAIT_SRC})