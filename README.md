# 🔍 Duplicate File Finder in C (Using SHA-256)

This project is a simple **Duplicate File Finder** written in the C language.  
It scans a directory, calculates the **SHA-256 hash** for each file using **OpenSSL**, and detects files with identical content.

---

## 🧠 Project Overview

When working with large directories, duplicate files can waste storage space.  
This program efficiently finds such duplicates by computing a **unique SHA-256 hash** for every file and comparing them using a **hash table**.

---

## ⚙️ Features

- ✅ Calculates **SHA-256 hash** of each file using OpenSSL  
- ✅ Detects **duplicate files** based on matching hashes  
- ✅ Uses a **hash table** for fast lookup  
- ✅ Lightweight and simple C implementation  

---

## 🧩 Requirements

To compile and run this project, ensure the following are installed:

- **C Compiler** (e.g., GCC)
- **OpenSSL Library**

