cmake_minimum_required(VERSION 2.8.0)

add_executable(client client.cpp)
target_link_libraries(client ${zmq_LIBRARY_NAME})

add_executable(server server.cpp)
target_link_libraries(server ${zmq_LIBRARY_NAME})

add_executable(client_2 client_2.cpp)
target_link_libraries(client_2 ${zmq_LIBRARY_NAME})

add_executable(server_2 server_2.cpp)
target_link_libraries(server_2 ${zmq_LIBRARY_NAME})
