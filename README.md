# Multithreaded Matrix Multiplication Benchmarking

## Overview

This Python script benchmarks the performance of matrix multiplication utilizing multithreading. It conducts matrix multiplication operations on a set of 100 randomly generated matrices, each of size 1000x1000, and multiplies them with a constant matrix of the same size. The performance metrics are recorded for different thread counts, ranging from 1 to 8.

## Prerequisites

- Python 3.x
- NumPy
- Matplotlib
- Pandas
- psutil (optional, for CPU usage monitoring)

## Outputs

The script generates the following outputs:

- A table displaying the time taken for matrix multiplication with varying numbers of threads.
- A graph plotting the matrix multiplication time against the number of threads used.
- Optionally, CPU usage data (if available).

## Results Interpretation

- **Time Taken (Sec):** Indicates the duration of matrix multiplication operations in seconds. Lower values represent better performance.
- **Number of Threads:** Denotes the count of threads employed for matrix multiplication. Increasing this count might enhance performance up to a certain threshold, depending on the system's capabilities.
- **CPU Usage:** Percentage of CPU utilization during the benchmarking process.

## Resulting DataFrame
![image](https://github.com/Bhavya2910/MultiThreadingAssignment/assets/99804770/c18506ff-4a61-44a8-8b38-72b269f2c317)
![image](https://github.com/Bhavya2910/MultiThreadingAssignment/assets/99804770/fa2d50b0-1cc2-4dcd-b7b6-7c93c99502ab)


