# OR-tools

## Description

 A build system for Google OR-tools.
 Current version: ORT-0.0.0.

## Installation Instructions

 1. Structure the project directory as follows.
 ```
    root
    ├── bin
    ├── include
    ├── lib
    ├── out
    └── src
 ```
    * The `src/` directory must contain the `.cpp` and `.hpp` or `.h` files.
    * The `out/` directory must be empty.
    * The other directories are their respective counter-parts from the Google OR-tools source code.
 2. Clone the repository while inside `root/`.
 ```shell
 git clone https://github.com/Phoenix-the-Imperial/OR-tools.git
 ```
 3. Move the `Makefile` to `root/`.
 4. Move the `CMakeLists.txt` to `root/src/`.
 5. Change `$(SRC_NAME)` in the `Makefile` to the name of the file containing the driver file if required.
 6. Change the name of the project and the executable in `CMakeLists.txt` if required.

## Version History

### Version ORT-0.0.0
 
 Initial commit. Added a `CMakeLists.txt` and a `Makefile` to be used as templates.
