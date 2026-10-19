# Graph-coloring-based register allocation

Global register allocation program that maps registers from variable live ranges, supporting web splitting and web spilling and using graph coloring algorithms in C++.

## Linux / MacOS build instructions

```
# -S: uses the current directory as the source directory
# -B: puts all the files on a folder called build
cmake -S . -B build
# calls the compiler to build the desired targets 
cmake --build build
# To run the tool
./RegisterAllocation
```

## Developers

This project was developed by:

* Gabriel Magalhães (up202405890)
* Guilherme Cunha (up202405961)
* Pedro Pires (up202405967)
