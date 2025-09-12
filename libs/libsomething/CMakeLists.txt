# CMakeLists.txt libsomething
add_library(libsomething src/something_delegate.cpp)
target_include_directories(libsomething PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/include)

# Si necesitas enlazar las librerías entre sí, puedes hacerlo aquí
# target_link_libraries(otra_libreria mi_libreria)

