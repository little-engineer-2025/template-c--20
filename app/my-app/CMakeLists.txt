# CMakeLists.txt my-app
add_executable(my-app src/main.cpp)
target_include_directories(my-app PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Si necesitas enlazar las librerías entre sí, puedes hacerlo aquí
# target_link_libraries(otra_libreria mi_libreria)

