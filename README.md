# File Compression Using Huffman Coding

A lossless text file compression and decompression system implemented in Python using **Huffman Coding** (Greedy Algorithm + Min-Heap Priority Queue).

## Features
- **Character Frequency Analysis:** Computes exact symbol frequencies across input text files.
- **Huffman Tree Construction:** Uses a binary min-heap (`heapq`) to merge lowest-frequency nodes greedily.
- **Prefix-Free Binary Encoding:** Generates optimal variable-length prefix codes and packs bitstreams into raw bytes.
- **Self-Contained `.huff` Format:** Serializes the frequency table in the file header so compressed files can be decoded independently.
- **Performance & Size Benchmarking:** Tracks original vs. compressed size, compression ratio, execution time (ms), and peak RAM usage (KB).

## How to Run

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd huffman-file-compression