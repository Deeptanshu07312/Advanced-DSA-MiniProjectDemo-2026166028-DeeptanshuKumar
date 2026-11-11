# Academic Records Indexer (BST)

## Overview
This repository contains a command-line student-record manager written in C. It was developed as an Advanced Data Structures mini-project for the M.Tech Artificial Intelligence and Data Science (AI & DS) program at CEG Campus, Anna University.

The system utilizes a Binary Search Tree (BST) architecture to efficiently manage, index, and retrieve student academic records—including CIA 1, CIA 2, and End-Semester marks—using the student's roll number as the primary key.

## Key Features
* **Efficient Core Operations:** Achieves O(log N) average time complexity for record insertion, searching, and deletion.
* **Sorted Marksheets:** Performs an O(N) in-order traversal of the BST to print the class marksheet in ascending roll order.
* **Runtime Benchmarking:** Implements runtime benchmarking using the `<time.h>` library to empirically test and chart the performance of BST operations.

## Repository Structure
* **Documentation:** `Academic_Records_Indexer_Report.pdf` and `Academic_Records_Indexer_Demo.pdf` contain the full project report and demonstration.
* **Performance Metrics:** `benchmark_results.csv`, `benchmark_output.txt`, and `benchmark_chart_output.png` showcase the runtime analysis of the data structure.
* **Tree Visualizations:** `tree_build_output.png`, `tree_search_output.png`, `tree_delete_output.png`, and `tree_degenerate_output.png` provide visual proofs of the tree state during various operations.
* **Data Outputs:** `students_sorted_out.csv` and `demo_transcript_output.txt` contain the processed, ordered data logs.

## Author
**Deeptanshu Kumar**
M.Tech AI & DS
