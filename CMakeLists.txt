cmake_minimum_required(VERSION 3.10)
project(tic_tac_toe_networking)

set(CMAKE_CXX_STANDARD 17)

add_executable(tic_tac_toe_networking clientMain.cpp connectsock.cpp getIPAddressInfo.cpp getServers.cpp passivesock.cpp playTictacToe.cpp serverMain.cpp TicTacToe.cpp TicTacToe.h timestamp.cpp UDP_recv.cpp UDP_send.cpp wait.cpp)