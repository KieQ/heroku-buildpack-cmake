Heroku buildpack: CMake
===================

This is the heroku buildpack for project using CMake.

**Notice**: 
```cmake
install(TARGETS ${TARGET_NAME} DESTINATION ..)
```

This line of cmake code must be provided.