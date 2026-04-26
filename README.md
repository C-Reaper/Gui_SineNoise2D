## Overview
The project is a C/C++ application that generates and displays 2D graphics using a sine wave function. The application supports building on Linux, Windows, Wine, and WebAssembly platforms.

## Features
- Generates 2D graphics based on a sine wave function.
- Displays the generated graphics in a window with mouse position information.
- Supports debugging for each platform.

## Project Structure
### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility
- Standard development tools
- Libraries needed in specific projects (example given WINAPI, X11)

## Build & Run
To build the project on a Linux system:
```sh
cd <Project>
make -f Makefile.linux all
```

To run the application on a Linux system:
```sh
make -f Makefile.linux exe
```

For clean rebuild on a Linux system:
```sh
make -f Makefile.linux clean
make -f Makefile.linux all
```

To build the project on a Windows system:
```sh
cd <Project>
make -f Makefile.windows all
```

To run the application on a Windows system:
```sh
make -f Makefile.windows exe
```

For clean rebuild on a Windows system:
```sh
make -f Makefile.windows clean
make -f Makefile.windows all
```

To build the project on a Wine system:
```sh
cd <Project>
make -f Makefile.wine all
```

To run the application on a Wine system:
```sh
make -f Makefile.wine exe
```

For clean rebuild on a Wine system:
```sh
make -f Makefile.wine clean
make -f Makefile.wine all
```

To build the project for WebAssembly using Emscripten:
```sh
cd <Project>
make -f Makefile.web all
```

To run the application in a web browser:
```sh
make -f Makefile.web exe
```