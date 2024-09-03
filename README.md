This repository contains implementations of three different path planning algorithms: A*, Jump Point Search (JPS), and an improved bidirectional Jump Point Search algorithm with parallel processing using OpenMP. The results of these algorithms are compared for different scenarios.

To compile the algorithms, a `Makefile` is provided. You can compile the executables using the following commands:

1. Compile all algorithms:

    ```bash
    make all
    ```

## Additional Files

- `dbscan.c`: This file is used to verify the detection of hotspot areas using the DBSCAN algorithm.
- `path.c`: Contains the implementation of the improved bidirectional JPS algorithm for path planning in a serial manner.
- `cluster.c`: Includes functionality for managing clusters in the path planning process.
- `map.c`: Common functionalities related to the map and environment representation.

## Running the Parallel Algorithm

To run the parallel implementation, you need access to the Seagull cluster, which is a high-performance computing environment. 

## MATLAB Files

MATLAB scripts are provided to visualize the results of these algorithms. These scripts also implement B-spline smoothing methods for creating smoother paths. Use the provided `.m` files to run the visualizations and observe the differences in path quality and algorithm performance.



