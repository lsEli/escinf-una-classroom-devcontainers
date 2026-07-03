# CMAKE options:

`-DCMAKE_TOOLCHAIN_FILE=/usr/local/vcpkg/scripts/buildsystems/vcpkg.cmake`

# CMakeLists.txt reminder:

```markdown
find_package(package_name_here CONFIG REQUIRED)

add_executable(project_name_here main.cpp)

target_link_libraries(project_name_here PRIVATE
    package_name_here::package_name_here
)
```
