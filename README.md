# Jakopter
Website : http://jakopter.irisa.fr/ (not available in english yet)

## Requirements
### Mandatory
CMake &ge; 2.8  
C compiler with C99 support (GCC or Clang)

### Optional
For Lua bindings : Lua 5.1 or 5.2

For video :
* FFMPEG (or at least libavcodec) for decoding
* SDL2 (for video display)
* SDL2_ttf (for text overlay within video display)

For Leap Motion control : Leap Motion SDK (and a C++ compiler)

For direct keyboard control : Curses.


## Build Instructions
The project uses CMake as a build system.

On UNIX systems you can generate a Makefile with the command:

    cmake .

Then you should be able to compile the project properly with:

    make

You can clear the files generated by CMake with:

    ./clear_cmake_generated_files

## How To Use
You can find the documentation on our main website (http://jakopter.irisa.fr).  
There are Lua examples in the test folder.

