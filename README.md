# Pastechi

A web server written in C++. (Continuation of http://github.com/gi0can/CppND-Capstone-miniHTTPD)

## Basic Build Instructions

### Linux, Mac
1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./minihttpd`.

### Windows
1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && msbuild minihttpd.sln /p:Configuration=Release`
4. Run it: `Release\minihttpd.exe`.

## Usage

### Start the server
./minihttpd 

### Add the files you want the server to serve in the directory "build/htdocs" 

### Connect to the server using your web browser by navigating to "http://localhost:8089"

