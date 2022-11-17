# SFML-Book (with FetchContent)

This fork automatically downloads and builds `SFML 2.6.x` under the hood.\
So, you don't need to worry about installing SFML manually.

+ Use `FetchContent()` to automatically download `SFML 2.6.x`
+ Static linking by default, copies `openal32.dll` on Windows
+ Export `compile_commands.json` with Ninja


## Build

After executing commands below, see `install/` directory for results.
```ps
cmake -S . -B build -DCMAKE_INSTALL_PREFIX=install -G Ninja
cmake --build build --target install
```

[See the original RemdMe.txt](ReadMe.txt) for more info.
