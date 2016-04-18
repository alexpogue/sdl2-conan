#Prerequisites

 - cmake
 - conan

#Building

`$ cd sdl2-conan`

Download dependencies:

`$ conan install`

(or use  `conan install --build SDL2` if conan.io doesn't have binary packages for your OS/architecture)

Generate project files using your favorite CMake generator:

`$ cmake .`

Build project (assuming "Unix Makefiles" CMake generator):

`$ make`

#Running

The project will build in sdl2-conan/bin.

To run on Unix environments:

`$ cd bin`

`$ ./sdl2-conan`
