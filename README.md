# conandemo-libfoo
Simple header-only C library

## Build steps

```bash
$ mkdir build && cd build
$ cmake .. -G "MSYS Makefiles" -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=$PWD/../install
-- The C compiler identification is GNU 10.3.0
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Check for working C compiler: C:/msys64/mingw64/bin/gcc.exe - skipped
-- Detecting C compile features
-- Detecting C compile features - done
-- Configuring done
-- Generating done
-- Build files have been written to: C:/msys64/home/kolekanos/conandemo-libfoo/build
$ cmake --build .
$ cmake --install .
-- Install configuration: "Release"
-- Installing: C:/msys64/home/kolekanos/conandemo-libfoo/install/share/Foo/cmake/FooConfig.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libfoo/install/share/Foo/cmake/FooConfigVersion.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libfoo/install/share/Foo/cmake/FooTargets.cmake
-- Installing: C:/msys64/home/kolekanos/conandemo-libfoo/install/include/foo
-- Installing: C:/msys64/home/kolekanos/conandemo-libfoo/install/include/foo/foo.h
$
```

