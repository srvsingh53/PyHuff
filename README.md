# PyHuff: Huffman Coding Compression and Decompression

## Introduction

PyHuff is a Python implementation of Huffman Coding, a widely used data compression algorithm.
The project enables you to compress and decompress text files using Huffman Coding, reducing file sizes efficiently.


Huffman Coding works by assigning variable-length codes to input characters based on their frequencies. Characters that occur more frequently receive shorter codes, resulting in efficient data compression.

## Implemented Data Structures

1. Huffman Tree
2. Min Heap(Priority_Queue)
3. Frequency Dictionary
4. Code Dictionary

## Usage

### Run the compression and decompression:

  1. To compress a text file, run:

      python main.py compress /path/to/your/input_file.txt

      The compressed file will be saved as /path/to/your/input_file.bin.

  3. To decompress a binary file, run:
  
       python main.py decompress /path/to/your/compressed_file.bin
     
       The decompressed text file will be saved as /path/to/your/compressed_file_decompressed.txt.

## Dependencies

The project has no external dependencies other than Python's standard library.

