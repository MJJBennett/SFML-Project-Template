### SFML/CMake Template

#### A simple project set up to show how easy it is to get started with an SFML project.

The code in this project is deliberately minimal; a window is created but nothing is drawn. It's meant as nothing more than a simple starting point for creating a project with SFML.

#### Setup

You'll need to download SFML (from [here](https://www.sfml-dev.org/download.php)) and extract/install it to `lib/SFML-2.4.2/`. Other names or locations can be used (including installation through a package manager) but this may require additional setup in the `CMakeLists.txt` file. The .DLL files in `SFML-2.4.2/bin` will need to be moved to the local `build/` directory, or the application will be unable to run.

#### Building and running:

* To run this project, you will need a C++ compiler, CMake, and potentially Make, depending on your setup.

* In `build/`, run `cmake ..` (or `cmake .. -G "Generator Name"`, i.e. `cmake .. -G "MinGW Makefiles"` depending on what build files you want CMake to generate)

* Run `make`

* Run `./EGProject` (extension depends on platform)