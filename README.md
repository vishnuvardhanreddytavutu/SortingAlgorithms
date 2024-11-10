# Sorting Algorithms Implementation

A collection of four classic sorting algorithms implemented in Java with benchmarking capabilities.

## Implemented Algorithms

1. **Quick Sort**
   - Average Time Complexity: O(n log n)
   - Partition-based sorting
   - In-place algorithm

2. **Merge Sort**
   - Time Complexity: O(n log n)
   - Divide and conquer algorithm
   - Stable sorting algorithm

3. **Heap Sort**
   - Time Complexity: O(n log n)
   - Heap data structure based
   - In-place algorithm

4. **Insertion Sort**
   - Time Complexity: O(n²)
   - Efficient for small data sets
   - Adaptive algorithm

## Usage

1. Compile all Java files:
```bash
javac *.java
```

2. Run the benchmark program:
```bash
java SortingBenchmark
```

## Benchmark Output Example

```
Sorting Algorithm Benchmark
==========================

Array size: 100
--------------
Quick Sort      :    0.123 ms : Sorted correctly: true
Merge Sort      :    0.156 ms : Sorted correctly: true
Heap Sort       :    0.189 ms : Sorted correctly: true
Insertion Sort  :    0.145 ms : Sorted correctly: true

Array size: 1000
--------------
Quick Sort      :    1.234 ms : Sorted correctly: true
Merge Sort      :    1.567 ms : Sorted correctly: true
Heap Sort       :    1.890 ms : Sorted correctly: true
Insertion Sort  :    4.567 ms : Sorted correctly: true
...
```

## Features

- Common interface for all sorting algorithms
- Random array generation for testing
- Automatic verification of sorting correctness
- Performance benchmarking across different array sizes
- Clean code with detailed comments
