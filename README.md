-----------------------------------

_DISCLAIMER:_

This repository is based on the raylib-game-template repository greated by Ramon Santamaria ([@raysan5](https://twitter.com/raysan5))_

-----------------------------------
## Getting started with this game

As of now I only support compiling this project using CMake on Windows. 

### CMake

- Extract the zip of this project
- Type the follow command:

```sh
cmake -S . -B build
```

> if you want with debug symbols put the flag `-DCMAKE_BUILD_TYPE=Debug`

- After CMake config you project build:

```sh
cmake --build build
```

- Inside the build folder are another folder (named the same as the project name on CMakeLists.txt) with the executable and resources folder.

### License

This game sources are licensed under an unmodified zlib/libpng license, which is an OSI-certified, BSD-like license that allows static linking with closed source software. Check [LICENSE](LICENSE) for further details.

$(Additional Licenses)

*Copyright (c) $(Year) $(User Name) ($(User Twitter/GitHub Name))*
