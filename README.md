# 💻 Data Compression using Huffman Encoding

### Created by:
1. **Abhinay Nachankar**  
2. **Raj Kavthekar**  
3. **Prakash Gond**

---

## 🧩 Project Overview

This project demonstrates **Data Compression using the Huffman Encoding Algorithm** — one of the most efficient and widely used techniques for lossless data compression.  
It provides a **modern, interactive GUI** that allows users to enter text, visualize frequency tables, generate Huffman codes, and view the encoded and decoded results in real time.

---

## 🎯 Objectives

- To understand and implement the **Huffman Coding Algorithm** for text compression.  
- To design an **interactive graphical user interface (GUI)** for better visualization and ease of use.  
- To compare the **original and compressed sizes** and calculate the **compression ratio**.  
- To enhance knowledge of **data structures (trees, heaps, and maps)** used in real-world applications.  
- To demonstrate how **lossless compression** works efficiently for character-based data.

---

## ⚙️ Prerequisites

Before running the project, ensure you have the following:

### 🐍 For Python Version:
- Python 3.8 or above  
- Tkinter (comes pre-installed with Python)  
- Basic understanding of Python programming and GUI concepts

### 🌐 For JavaScript (Web) Version:
- A modern web browser (Google Chrome, Edge, Firefox, etc.)  
- Basic HTML, CSS, and JavaScript knowledge  
- Any text editor (VS Code recommended)

---

## 🚀 Features

- ✅ Encode and Decode text using Huffman Algorithm  
- ✅ Display of character frequencies and generated Huffman codes  
- ✅ Real-time calculation of compression ratio  
- ✅ Clean, modern UI for a smooth user experience  
- ✅ Clear and reset functionalities for multiple tests  

---

## 🔁 Huffman Encoding Flowchart

Below is a simple visual representation of how the Huffman Encoding process works 👇  

```mermaid
flowchart TD
    A[Start] --> B[Input Text]
    B --> C[Calculate Frequency of Each Character]
    C --> D[Create Priority Queue (Min-Heap)]
    D --> E[Build Huffman Tree by Merging Lowest Frequency Nodes]
    E --> F[Generate Binary Codes (0/1) from Tree Paths]
    F --> G[Encode Original Text using Generated Codes]
    G --> H[Display Encoded Output and Compression Ratio]
    H --> I[Decode Back using Huffman Tree]
    I --> J[Display Decoded Text]
    J --> K[End]
