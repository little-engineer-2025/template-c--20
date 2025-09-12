# CMakeLists.txt my-tool
add_executable(my-tool src/main.cpp)
target_include_directories(my-tool PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Si necesitas enlazar las librerías entre sí, puedes hacerlo aquí
# target_link_libraries(otra_libreria mi_libreria)

