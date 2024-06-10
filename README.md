# Quick Sort Implementation Using 8085 Assembly Language

## Project Overview

This project implements the Quick Sort algorithm using the 8085 assembly language. The primary goal is to enhance understanding of microprocessor-based programming and optimize sorting efficiency in terms of speed and resource utilization. This project translates a high-level algorithm into low-level assembly instructions specific to the 8085 microprocessor, providing a practical example for educational purposes.

## Objectives

- **Implement Quick Sort**: Translate the Quick Sort algorithm into 8085 assembly language.
- **Optimize Efficiency**: Achieve efficient sorting in terms of speed and resource utilization.
- **Educational Value**: Enhance understanding of assembly language and microprocessor programming.
- **Systematic Testing and Debugging**: Ensure the correctness and robustness of the implementation through thorough testing and debugging.
- **Documentation**: Provide comprehensive documentation detailing the implementation process, design choices, challenges, and solutions.

## Quick Sort Algorithm Overview

Quick Sort is a comparison-based sorting algorithm known for its performance and simplicity. It uses a divide-and-conquer strategy:

1. **Pivot Selection**: Choose an element from the array as the pivot. Methods for selecting the pivot include the first element, the last element, the middle element, or a random element.
2. **Partitioning**: Rearrange the elements so that those less than the pivot come before it and those greater than the pivot come after it.
3. **Recursive Sorting**: Apply the same process recursively to the sub-arrays of elements with smaller and larger values.

## Implementation Details

### System Requirements

- **GNUSim8085**: A graphical simulator, assembler, and debugger for the Intel 8085 microprocessor architecture.
- **Operating System**: Any OS capable of running GNUSim8085.

### Key Steps in Implementation

1. **Initialization**: Generate random numbers to populate the array starting at memory address 2000H.
2. **Data Transfer**: Move the generated values to the array starting at memory address 2100H.
3. **Partitioning**: Implement the partitioning logic to rearrange the elements based on the pivot.
4. **Recursive Sorting**: Implement recursive calls to sort the sub-arrays.

### Debugging and Testing

- **Step-by-Step Execution**: Utilize the GNUSim8085 simulator to execute the program step-by-step, ensuring the correctness of each instruction.
- **Memory Inspection**: Verify the initial unsorted array and the final sorted array by inspecting memory addresses.
- **Register Values**: Check the final state of the registers to ensure correct execution of the sorting process.
- **Test Cases**: Run multiple test cases with different initial arrays to confirm the algorithm's correctness.

## Results Analysis

- **Input Array**: The initial array is stored at memory addresses starting from 2000H.
- **Sorted Array**: The sorted array is stored at memory addresses starting from 2100H.
- **Registers**: Final register values reflect the end state of the sorting process.

## Conclusion and Future Improvements

The project successfully demonstrates the Quick Sort algorithm using 8085 assembly language. It provides valuable insights into low-level programming and the implementation of recursive functions. The project highlights the efficiency achieved and the learning outcomes.

### Future Improvements

1. **Optimize Pivot Selection**: Improve the pivot selection method to reduce the likelihood of worst-case scenarios.
2. **Handle Larger Datasets**: Enhance memory management to better handle larger datasets.
3. **Explore Other Sorting Algorithms**: Compare the performance of Quick Sort with other sorting algorithms for educational purposes.
4. **Manage Recursion**: Address the complexity of managing recursive calls in assembly language, possibly exploring iterative solutions.

## Bibliography

- “8085 Microprocessor Assembly Language Programming” by Samir G. Pandya
- "The Art of Computer Programming, Volume 3: Sorting and Searching" by Donald E. Knuth
- “The Art of Assembly Language Book” by Randall Hyde
- GNUSim8085 official documentation and user guide
- Research articles and online tutorials on Quick Sort and 8085 assembly language programming


