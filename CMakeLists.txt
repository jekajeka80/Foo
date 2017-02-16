project(Foo)

set(SOURCE_EXE appFoo.cpp)
set(SOURCE_LIB Foo.cpp)
add_library(Foo SHARED ${SOURCE_LIB})
add_executable(appFoo ${SOURCE_EXE})
target_link_libraries(appFoo Foo)

