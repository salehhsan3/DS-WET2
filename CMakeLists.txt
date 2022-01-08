cmake_minimum_required(VERSION 3.16)
project(wet2)

set(CMAKE_CXX_STANDARD 14)

add_executable(SIVANSGAME RankTree.h DynamicArray.h UnionFind.h  SivansGame.h SivansGame.cpp
                                        library2.cpp main.cpp Group.cpp Player.h )


        