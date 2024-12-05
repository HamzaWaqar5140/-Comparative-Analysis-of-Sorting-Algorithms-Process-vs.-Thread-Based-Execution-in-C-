1. Project Title
"Comparative Analysis of Sorting Algorithms: Process vs. Thread-Based Execution in C"
3. Objectives
To implement multiple sorting algorithms (Bubble Sort, Selection Sort, Insertion Sort, Quick Sort, Merge Sort).
To compare the execution times of sorting algorithms using:
Process-based execution.
Thread-based execution.
To analyze the performance of sorting methods with varying input sizes.
To store sorted outputs and log results for analysis.
4. Features
Sorting Algorithms:
Bubble Sort
Selection Sort
Insertion Sort
Quick Sort
Merge Sort
Process-Based Execution: Each sorting algorithm is executed as a separate process.
Thread-Based Execution: Each sorting algorithm is executed as a separate thread.
Performance Metrics: Measures execution time for both processes and threads.
File Integration: Reads input data from a file (Numbers.txt) and writes sorted output to sorted.txt.
5. Methodology
Input Preparation:
A file (Numbers.txt) containing random integers is used as input.
Algorithm Implementation:
Sorting algorithms are implemented in both process-based and thread-based paradigms.
Process functions will be defined in Processes.h.
Thread functions will be defined in Threads.h.
Performance Measurement:
Execution times are measured using clock_gettime() for both approaches.
Results are displayed and logged.
Output Generation:
Sorted arrays are stored in sorted.txt.
Comparison:
Execution times for processes and threads are compared for each algorithm.
6. Tools and Technologies
Programming Language: C
Development Environment: Ubuntu 22.04
Compiler: GCC with pthread library
7. Expected Outcome
A detailed comparison of the performance of sorting algorithms executed as processes versus threads.
Insights into the trade-offs between process-based and thread-based execution.
Optimized code for sorting operations based on performance analysis.

9. Applications
Efficient sorting for large-scale data processing.
Educational purposes to understand process vs. thread execution.
Basis for advanced parallel computing research.
10. Conclusion
This project will provide a comprehensive understanding of the efficiency of sorting algorithms when executed as processes or threads. The insights gained will be valuable for optimizing performance in multi-core and multi-threaded computing environments.
