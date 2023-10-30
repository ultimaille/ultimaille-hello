# ultimaille-hello

This project shows how to configure `CMakeList.txt` in order to use ultimaille in your own project. It can be a good starting point if you want to use ultimaille in a project you build from scratch.

# Build

Before build, we recommend to create a `build` directory that will contains generated MakeFile, the ultimaille sources and generated executables.

```
mkdir build && cd build && cmake .. && make
```

# Run 

Go to the `build` directory and run the `hello_ultimaille` executable.

# Clean

To clean, just remove the build directory: `rm -drf build`