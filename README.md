# Simple Text Editor (C/C++)

A **medium-sized open-source project** where we build a **minimal text editor from scratch** using **C++**, while heavily relying on **low-level C system programming** concepts.

This project is inspired by how early Unix editors worked and focuses on understanding **terminals, raw mode, file I/O, and process interaction** rather than features or UI polish.

---

## 🚀 Features

- Raw terminal input handling (`termios`)
- Character-by-character reading
- Basic screen rendering
- Keyboard control handling (Ctrl keys, escape sequences)
- File loading and saving
- Minimal editor loop (no external libraries)

---

## 🛠️ Tech Stack

- **Language:** C++ (with extensive use of C APIs)
- **System Interfaces:**
  - `unistd.h`
  - `termios.h`
  - `errno.h`
- **Platform:** Unix / Linux (POSIX-compliant systems)

> Although written in C++, the project intentionally avoids STL-heavy abstractions to stay close to the OS.


