## Assiut Training - Newcomers (Structured Solutions & Templates)

<div align="center">
    <a href="https://codeforces.com/group/MWSDmqGsZm/contests">
        <img src="https://raw.githubusercontent.com/MinaFaried3/Assiut-University-Training---Newcomers/refs/heads/main/download.png" alt="Assiut Newcomers Training" width="50px">
    </a>

</div>

### [📚 Access Official Contest Sheets](https://codeforces.com/group/MWSDmqGsZm/contests)

---

## Overview

This repository provides solutions and C++ starter templates for the **Assiut Training - Newcomers** problem sheets hosted on Codeforces.

The goal of this repository is to offer a **structured and organized** way to approach the training material, particularly for those who prefer to:

1. Download the problem set structure for offline access.
2. Attempt problems using a provided template *before* looking at a potential solution.
3. Have solutions readily available but kept separate from the initial problem file.

## Repository Structure

Each sheet from the training has its own dedicated folder, named like `Sheet #X (Topic Name)`. Inside each sheet folder, you will typically find:

* **Problem Template Files (`.cpp`):** Named like `A-ProblemName.cpp`, `B-ProblemName.cpp`, etc. These files contain a basic C++ template (see below) including comments indicating where to read input, write your solving logic, and print the output. Use these to start coding your own solution!
* **`solutions/` Folder:** This subfolder contains the corresponding solution files for the problems in that sheet. The filenames within `solutions/` match the template filenames in the parent directory (e.g., `solutions/A-ProblemName.cpp` contains the solution for `A-ProblemName.cpp`).

```
Assiut-Contests/
│
├── Sheet #1 (Data type - Conditions)/
│   ├── A-Say-Hello-With-C++         <-- Problem Template
│   ├── B-Basic-Data-Types.cpp          <-- Problem Template
│   ├── ...
│   └── solutions/
│       ├── A-Say-Hello-With-C++     <-- Solution File
│       ├── B-Basic-Data-Types.cpp      <-- Solution File
│       └── ...
│
├── Sheet #2 (Loops)/
│   ├── ...
│   └── solutions/
│       └── ...
│
├── ... (Other Sheets)
│
└── README.md
```

## How to Use

1. Navigate to the folder corresponding to the sheet you are working on (e.g., `Sheet #1 (Data type - Conditions)`).
2. Open the `.cpp` file for the problem you want to solve (e.g., `A-Say-Hello-With-C++`).
3. Use the provided template structure within that file to write and test your own solution.
4. **After attempting the problem yourself**, if you need help or want to compare your approach, look inside the `solutions/` subfolder for the corresponding solution file (e.g., `solutions/A-Say-Hello-With-C++`).

## C++ Template Example (`B-Delete-from-the-Left.cpp`)

The template files provide a basic structure like this:

```cpp
// Problem: [Problem Name] (e.g., Delete from the Left)
// URL: [Problem Link] (e.g., https://codeforces.com/group/MWSDmqGsZm/contest/223340/problem/B)
// Memory Limit: [Limit] MB (e.g., 256 MB)
// Time Limit: [Limit] s (e.g., 1 s)

#include <iostream> // Or other necessary headers
// #include <string>
// #include <vector>
// #include <algorithm>

using namespace std;

int main() {
    // Optimize input/output (optional but recommended for CP)
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);
    cout.tie(NULL);

    // Read input
    // --- Your input reading code here ---


    // Solve problem
    // --- Your core logic code here ---


    // Print output
    // --- Your output printing code here ---


    return 0;
}
```

## Acknowledgements

The core solutions presented in the `solutions/` folders are based on the excellent work done by **Mina Faried**. His original repository, which contains solutions and explanations, can be found here:

* **Original Repository:** [MinaFaried3/Assiut-University-Training---Newcomers](https://github.com/MinaFaried3/Assiut-University-Training---Newcomers)
* **Author Profile:** [Mina__Faried on Codeforces](https://codeforces.com/profile/Mina__Faried)

This repository primarily aims to **reorganize** that content into a structure that facilitates practice by separating the problem template from the final solution, making it easier for learners to attempt problems independently first. A huge thank you to Mina Faried for making his solutions publicly available!

---

Happy Coding!
