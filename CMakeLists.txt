PROJECT(demo_daemon)
CMAKE_MINIMUM_REQUIRED(VERSION 2.8)
AUX_SOURCE_DIRECTORY(. DIR_SRCS)
ADD_EXECUTABLE(demo_daemon ${DIR_SRCS})
