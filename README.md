### TODOlist

📝 A simple to-do list app built using **C++**, **SFML**, and **CMake** inside **Visual Studio**.

This project is both a learning tool and a lightweight task management program. It features a visual 
interface powered by SFML, with plans for features like adding, removing, and checking off tasks.

---

### 💻 Requirements

- [SFML 3.0.0](https://www.sfml-dev.org/)
- [CMake](https://cmake.org/)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) (with "Desktop development with C++" workload)

---

## 🛠️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/TODOlist.git
Open Visual Studio, go to:

mathematica
Copy
Edit
File → Open → CMake...
Select the root folder of this project (TODOlist)

Visual Studio will automatically detect the CMakeLists.txt file and configure the project.

Press Ctrl + F5 or use the green “Run” button to build and run the project.

### 🧱 Project Structure

TODOlist/
├── CMakeLists.txt
├── main.cpp
├── src/
├── include/
└── README.md

### 🔧 CMake Notes
This project uses CMake’s FetchContent to automatically download and build SFML alongside your code.
To change the SFML version, edit the GIT_TAG in CMakeLists.txt.

### 📌 License
This project is licensed under the MIT License or Public Domain — whichever you prefer.

### 🎯 Goals
 Basic SFML window

 Add visual to-do list

 Task creation & removal

 File saving/loading

 Sorting, reminders, etc.

---
