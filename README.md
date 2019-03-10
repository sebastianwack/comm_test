# Test program for the AnyDSL Communicator

# Build and run

Make sure impala and clang are on the PATH.

    mkdir build
    cd build
    cmake .. -DAnyDSL_runtime_DIR:PATH="<add path to anydsl runtime here>/build/share/anydsl/cmake"
    make

    mpirun -n 2 src/main
