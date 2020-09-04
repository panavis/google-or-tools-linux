# Google Or-Tools Linux Native Library

Generated using `cmake`

https://github.com/google/or-tools/blob/stable/cmake/doc/java.md

```
cmake -S. -Bbuild -DBUILD_JAVA=ON .
cmake --build .
cmake --build . --target java_package
```
**Note**: Execute those commands in the root directory of the repository.  
Otherwise, replace '.' with the actual source directory.

Java classes and JNI libraries will be generated in `or-tools/java` 

