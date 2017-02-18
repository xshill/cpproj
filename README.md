#cpproj

A simple script for creating a directory structure for C++ projects that use CMake, Doxygen and
Google Test. Also includes a .gitignore file.

##Usage

Run `/path/to/cpproj/cpproj project_name` to create a project for an executable.  
Run `/path/to/cpproj/cpproj project_name --library` to create a project for a library.

##The structure

- `build`: this is the directory from which CMake should be run.
- `doc`: this is the directory in which documentation is built using Doxygen.
- `include/project_name`: this is where you should put your include files.
- `src`: this is where you should put your source files.
- `test/test_project_name`: this is where you should put your test files.
