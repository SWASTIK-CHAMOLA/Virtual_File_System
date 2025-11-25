# Virtual File System (VFS) Simulator

The **Virtual File System (VFS) Simulator** is a Python-based desktop application built using **Tkinter**. It provides an educational and interactive way to understand how modern operating systems manage files, directories, inodes, dentries, and caching mechanisms.

---

## 🚀 Overview

This simulator abstracts low-level storage details and presents a virtual hierarchical file system. Users can interact with it through a modern GUI while the backend tracks every system call and displays live caching statistics.

Ideal for:
- Operating System courses  
- Students learning file system internals  
- Demonstrations of directory traversal, caching, system calls, and inode/dentry usage  

---

## 🧩 Key Features

### ⭐ Modern GUI Interface
- Built with Tkinter.
- Dark-themed and user-friendly layout.
- Supports navigation via buttons and double-clicks.

### ⭐ Virtual File System Model
- Simulates directories and files.
- Unique inode numbers for each object.
- Tracks metadata:  
  - Name  
  - Type (FILE / DIR)  
  - Size or item count  
  - Inode  
  - Creation timestamp  

### ⭐ System Call Logging
Records the last 50 operations such as:  
`CREATE`, `DELETE`, `CHDIR`, `READDIR`, `READ`, `WRITE`, etc.

Each log entry includes:
- Timestamp  
- Operation type  
- Target path  
- Status  

### ⭐ Caching Simulation
Includes:
- **Dentry Cache**
- **Inode Cache**

Tracks:
- Cache Hits  
- Cache Misses  
- Cache Hit Rate  

Includes a **Clear Cache** button for demonstrations.

### ⭐ Statistics Panel
Displays:
- Total files  
- Total directories  
- Total operations performed  
- Cache metrics  
- Currently mounted filesystem type  

### ⭐ Multi-Filesystem Support
Allows mounting different filesystem types (simulation only):
- EXT4  
- NTFS  
- BTRFS  
- (Extensible architecture)  

---

## 🛠️ Installation & Running

### Prerequisites
- Python **3.x**
- Uses only Python’s built-in libraries

### Running the Application

1. Save your program code as:

