# Effective Water Simulation from Physical Models
From [GPU Gems book 1, part 1, chapter 1.](https://developer.nvidia.com/gpugems/gpugems/part-i-natural-effects/chapter-1-effective-water-simulation-physical-models)
 Mark Finch, Cyan Worlds

## Concepts Implemented
* Sum of sines approximation
* Gerstner waves
* Edge-length filtering

## Visuals
![water anim](https://user-images.githubusercontent.com/42471346/173206974-f3ade3ae-2949-46ce-887c-9e9e5c5afa35.gif)

## Concepts Reimagined
* TBD

## Concepts explored/reimplemented in other repositories
* TBD

## Compilation and installation instructions
The graphics for this engine are handled using OpenGL, and the following instructions are for setting up the code in Windows. 

### Required packages
Compiler used:
* Minimalist GNU for Windows ([MinGW](https://sourceforge.net/projects/mingw/))
  * A GCC Compiler

Libraries required for default program compilation and installed under dependency folder:
* [OpenGL](https://github.com/KhronosGroup/OpenGL-Registry)
* The OpenGL Extension Wrangler Library ([GLEW](https://github.com/nigels-com/glew))
* Simple DirectMedia Layer ([SDL](https://github.com/libsdl-org/SDL))
  * SDL Image

### Instructions
* All dependencies are stored within the repository. Once MinGW is installed, make sure you add ~\MinGW\bin to the PATH environment variable using these [instructions](http://www.mingw.org/wiki/Getting_Started/). Make can be called, and the executable ./EWS.exe ran with no additional parameters.
  * Note that you may have to adjust the name of the MinGW make executable. The executable may exist as mingw32-make, but can be renamed to make as necessary. However, you may or may not want to follow through with this action depending on the compilers that you have installed previously.

## License
[MIT License](https://choosealicense.com/licenses/mit/)
