# Huffman-Coding
📌 Project Overview

This project implements Huffman Coding, a lossless data compression algorithm, to compress and decompress .txt files efficiently.
The software reduces file size while preserving the original data, making it suitable for storage optimization and faster file transmission.

The project is implemented in C++ using priority queues and binary trees, showcasing strong fundamentals of Data Structures and Algorithms.

🎯 Objectives

Implement Huffman Coding from scratch

Achieve lossless text file compression

Reduce file size without losing information

Demonstrate practical use of trees and greedy algorithms

🛠️ Key Features

📄 Compress .txt files

🔓 Decompress files back to original form

🌳 Binary Tree–based Huffman structure

⚡ Efficient encoding using variable-length codes

📉 Significant reduction in file size

🧪 Accurate reconstruction of original data

🧠 Huffman Coding – Concept

Huffman Coding assigns:

Shorter codes to frequently occurring characters

Longer codes to less frequent characters

This results in optimal prefix codes and minimizes overall file size.

🧩 Project Workflow

Read input text file

Calculate character frequencies

Build a Min Heap (Priority Queue)

Construct Huffman Tree

Generate binary codes for each character

Encode the file and store compressed output

Decode using the same tree to retrieve original text

📂 Project Structure
Huffman-Coding/
│── src/
│   ├── huffman.cpp
│
│── input/
│   ├── sample.txt
│
│── output/
│   ├── compressed.huff
│   ├── decompressed.txt
│
│── README.md

⚙️ Technologies Used

Language: C++

Data Structures:

Priority Queue (Min Heap)

Binary Tree

Algorithm:

Greedy Algorithm (Huffman Coding)

Learning Outcomes

Strong understanding of greedy algorithms

Practical implementation of trees and heaps

Knowledge of lossless compression techniques

Experience with file handling in C++

📌 Use Cases

Text file compression

Storage optimization

Data transmission efficiency

Academic projects & DSA interviews

🔮 Future Enhancements

Support for binary files (images, PDFs)

GUI-based compression tool

Improved compression statistics

Multi-file compression support
