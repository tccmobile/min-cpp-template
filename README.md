# Hello World CMake Project

A simple Hello World program built with CMake.

## Prerequisites

- CMake (version 3.10 or higher)
- C++ compiler (supporting C++17)

## Project Structure

```
.
├── CMakeLists.txt          # Root CMake configuration
├── src/
│   ├── CMakeLists.txt      # Source-specific CMake configuration
│   └── main.cpp           # Main source file
├── LICENSE
└── README.md
```

## Building the Project

1. Create and enter a build directory:
   ```bash
   mkdir build
   cd build
   ```

2. Generate build files:
   ```bash
   cmake ..
   ```

3. Build the project:
   ```bash
   make
   ```

## Running the Program

After building, run the program from the build directory:

```bash
./src/hello_world
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
