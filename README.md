Heroku buildpack: CMake
===================

This is the heroku buildpack for project using CMake.

**Notice**: 
```cmake
install(TARGETS ${TARGET_NAME} DESTINATION ${CMAKE_CURRENT_BINARY_DIR}/..)
```

This line of cmake code must be provided.