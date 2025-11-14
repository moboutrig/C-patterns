# The Algorithms - C # {#mainpage}
### Your C Programming Roadmap

It's an excellent idea to approach this large repository with a clear plan. Instead of getting overwhelmed, you can build your knowledge step-by-step. This guide breaks down the folders by difficulty to create a personalized learning path for you.

---

### Level 1: Beginner (Focus on these first)

These folders contain the absolute fundamentals of algorithms and data structures. Mastering these will give you a strong foundation in C and computational thinking.

*   **`math/`**
    *   **What it is**: Basic mathematical algorithms.
    *   **Why it's for beginners**: These are small, self-contained problems that are perfect for learning C syntax, loops, and basic problem-solving.
    *   **Where to start**: `factorial.c`, `gcd.c` (Greatest Common Divisor), `prime.c`, `fibonacci.c`.

*   **`conversions/`**
    *   **What it is**: Algorithms for converting numbers between different bases (like binary to decimal).
    *   **Why it's for beginners**: Excellent for understanding how numbers are represented in memory and for practicing basic string manipulation.
    *   **Where to start**: `binary_to_decimal.c`, `decimal_to_binary.c`.

*   **`searching/`**
    *   **What it is**: Essential algorithms for finding data within a collection.
    *   **Why it's for beginners**: `linear_search.c` is one of the simplest algorithms to exist, and `binary_search.c` is a fundamental "divide and conquer" concept that every programmer must know.
    *   **Where to start**: `linear_search.c`, `binary_search.c`.

*   **`sorting/` (The Basics)**
    *   **What it is**: Core algorithms for arranging data in order.
    *   **Why it's for beginners (some of them)**: Simple sorting algorithms are great for understanding nested loops and array manipulation.
    *   **Where to start**: `bubble_sort.c`, `insertion_sort.c`, `selection_sort.c`. (Save the more complex ones for the intermediate level!)

*   **`data_structures/` (The Foundations)**
    *   **What it is**: Implementations of the most important data structures. This is a crucial folder.
    *   **Why it's for beginners**: Understanding these is key to becoming a competent programmer. They are the building blocks for solving almost any other problem.
    *   **Where to start**:
        *   `array/`: To understand basic array operations.
        *   `linked_list/`: The cornerstone of dynamic data structures. Start with `singly_link_list.c`.
        *   `stack/` and `queue/`: Fundamental "first-in, last-out" and "first-in, first-out" structures.

---

### Level 2: Intermediate (Explore these next)

Once you're comfortable with the basics, these folders introduce more complex algorithms and data structures that build upon the fundamentals you've learned.

*   **`data_structures/` (Advanced Parts)**
    *   **What it is**: More complex data structures that often use recursion and more advanced pointer logic.
    *   **Where to start**: `binary_trees/`, `graphs/`, `heap/`, `hash_table/`.

*   **`sorting/` (Advanced Parts)**
    *   **What it is**: More efficient but complex sorting algorithms.
    *   **Why it's intermediate**: Algorithms like Merge Sort and Quick Sort use recursion and are more abstract than the simple sorts.
    *   **Where to start**: `merge_sort.c`, `quick_sort.c`.

*   **`cipher/`**
    *   **What it is**: Simple encryption algorithms.
    *   **Why it's intermediate**: Good practice for character and string manipulation, and they are slightly more complex than the basic math problems.
    *   **Where to start**: `rot13.c`, `caesar.c`.

*   **`dynamic_programming/` and `greedy_approach/`**
    *   **What they are**: These are powerful problem-solving *techniques* rather than single algorithms.
    *   **Why they are intermediate**: They require a more abstract way of thinking. It's best to tackle these after you are comfortable with recursion and basic data structures.

*   **`games/`**
    *   **What it is**: Simple command-line games.
    *   **Why it's intermediate**: A fun way to apply your knowledge to a slightly larger project. `tic_tac_toe.c` is a great place to begin.

---

### Level 3: Advanced (Save these for later)

These topics are highly specialized or require significant external knowledge (like advanced math or operating systems concepts). Don't worry about these until you are very confident in your C and algorithm skills.

*   **`machine_learning/`**: Requires a strong background in mathematics (linear algebra, statistics).
*   **`numerical_methods/`**: Involves concepts from calculus and numerical analysis.
*   **`client_server/` and `graphics/`**: These are entire fields of computer science that involve interacting with operating systems, network sockets, or graphics libraries (like OpenGL), adding a lot of complexity.
*   **`developer_tools/`**: Contains custom tools for debugging memory allocation. This is an advanced "meta" topic—it's a tool to help you find bugs in other C programs.
*   **`leetcode/` and `project_euler/`**: These are large collections of solutions to competitive programming problems. They are excellent for practice *after* you have a good grasp of the intermediate topics.

---

### Project & Tooling Folders (Safe to ignore)

These folders and files do not contain C algorithms for you to learn. They are used to manage, build, and test the project itself. You do not need to understand them to learn from the source code.

*   `.github/`: Used for GitHub Actions (automated testing).
*   `scripts/`: Contains helper scripts for project maintenance.
*   `CMakeLists.txt`: Build system files used by CMake to compile the code.
*   **All files starting with a dot (`.`):** These are configuration files (e.g., `.clang-format`, `.gitpod.yml`).
*   **Markdown files**: `README.md`, `CONTRIBUTING.md`, etc. are documentation.


The repository is a collection of open-source implementations of a variety of algorithms implemented in C and licensed under [GPLv3 License](https://github.com/TheAlgorithms/C/blob/master/LICENSE). The algorithms span a variety of topics from computer science, mathematics and statistics, data science, machine learning, engineering, etc.. The implementations and their associated documentations are meant to provide a learning resource for educators and students. Hence, one may find more than one implementation for the same objective but using different algorithm strategies and optimizations.

## Features

* The repository provides implementations of various algorithms in one of the most fundamental general purpose languages - [C](https://en.wikipedia.org/wiki/C_(programming_language)).
* Well documented source code with detailed explanations provide a valuable resource for educators and students alike.
* Each source code is atomic using standard C library [`libc`](https://en.wikipedia.org/wiki/C_standard_library) and _no external libraries_ are required for their compilation and execution. Thus the fundamentals of the algorithms can be studied in much depth.
* Source codes are [compiled and tested](https://github.com/TheAlgorithms/C/actions?query=workflow%3A%22Awesome+CI+Workflow%22) for every commit on the latest versions of two major operating systems viz., MacOS and Ubuntu (Linux) using AppleClang 14.0.0 and GNU 11.3.0 respectively.
* Strict adherence to [C11](https://en.wikipedia.org/wiki/C11_(C_standard_revision)) standard ensures portability of code to embedded systems as well like ESP32, ARM Cortex, etc. with little to no changes.
* Self-checks within programs ensure correct implementations with confidence.
* Modular implementations and OpenSource licensing enable the functions to be utilized conveniently in other applications.

## Documentation

[Online Documentation](https://TheAlgorithms.github.io/C) is generated from the repository source codes directly. The documentation contains all resources including source code snippets, details on execution of the programs, diagrammatic representation of program flow, and links to external resources where necessary.
Click on [Files menu](https://TheAlgorithms.github.io/C/files.html) to see the list of all the files documented with the code.

[Documentation of Algorithms in C](https://thealgorithms.github.io/C) by [The Algorithms Contributors](https://github.com/TheAlgorithms/C/graphs/contributors) is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)<br/>
<a href="https://creativecommons.org/licenses/by-sa/4.0"><img alt="Creative Commons License" style="height:22px!important;margin-left: 3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" /><img  alt="Credit must be given to the creator" style="height:22px!important;margin-left: 3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg" /><img alt="Adaptations must be shared under the same terms" style="height:22px!important;margin-left: 3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" /></a>

## Contributions

As a community developed and maintained repository, we welcome new un-plagiarized quality contributions. Please read our [Contribution Guidelines](https://github.com/TheAlgorithms/C/blob/master/CONTRIBUTING.md).
