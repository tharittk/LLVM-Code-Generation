# How-to-Build-an-LLVM-Backend
How to Build an LLVM Backend, published by Packt

Navigate in the different `chX` directory and look at the examples provided and
do the exercises when applicable.
Each directory has its own README.md with specific directions.

Note:
The exercises have been tested with the open source repository of LLVM at the
Git hash a4bf6cd7cfb1 from September 17th 2024. Which is LLVM 19.1.0.

Some of the exercises interact directly with the LLVM C++ API.
This API has no stability guarantee therefore it is possible that newer or older
version of LLVM will not work with these exercises.

For the exercices that requires a version of LLVM handy, if you build your own make sure to use the `CMAKE_INSTALL_PREFIX` cmake variable to set the install path, then build the `install` target.

Then, you will need to provide this path to CMake in the different exercise.

Follow the READMEs in the different directories when you get there.
