# RayCastingBattle
RayCasting FPS in C++

# Installation

## OS X

```
mkdir build-xc && cd build-xc
cmake .. -G Xcode
open RayCastingBattle.xcodeproj
```
(UNIX method is also working (see below) if you don't [need|want] to use Xcode)

## Windows

1. Create folder build-vs
2. Open cmake-gui
3. Source Folder /path/to/project
4. Build Folder /path/to/project/build-vs
5. Open ./build-vs/RayCastingBattle.sln

## UNIX

```
mkdir build-unix && cd build-unix
cmake ..
make
```
