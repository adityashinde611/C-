
## C / C++ 

### **1. Basics of C / C++**

* History & differences between C and C++
* Structure of a program (`main`, headers, compilation steps)
* Data types & variables
* Constants & literals
* Input/Output (`cin/cout` in C++, `scanf/printf` in C)
* Operators: arithmetic, relational, logical, bitwise, assignment, conditional, precedence/associativity
* Typecasting (implicit, explicit, `static_cast`, `reinterpret_cast`, `dynamic_cast`, `const_cast`)
* Comments & coding style

---

### **2. Control Flow**

* Conditional statements (`if`, `else`, `switch`)
* Loops (`for`, `while`, `do-while`)
* Break, continue, goto
* Nested loops
* Scope and lifetime of variables (`local`, `global`, `static`)

---

### **3. Functions**

* Defining & declaring functions
* Parameter passing (by value, by pointer, by reference)
* Function overloading (C++ only)
* Default arguments
* Inline functions
* Recursion
* Storage classes (`auto`, `static`, `extern`, `register`, `mutable` in C++)

---

### **4. Arrays & Strings**

* Single and multi-dimensional arrays
* Character arrays (C-style strings)
* String handling functions (`strlen`, `strcpy`, etc.)
* Introduction to `std::string` in C++

---

### **5. Pointers**

* Basics of pointers
* Pointer arithmetic
* Pointers & arrays
* Pointers & functions
* Void pointers
* Function pointers
* Pointer to pointer
* Wild, dangling, and null pointers
* Smart pointers (C++ – `unique_ptr`, `shared_ptr`, `weak_ptr`)

---

### **6. Memory Management**

* Stack vs Heap
* `malloc`, `calloc`, `realloc`, `free` (C)
* `new` and `delete` (C++)
* Memory leaks & dangling pointers
* RAII (Resource Acquisition Is Initialization)
* Move semantics & rvalue references
* Memory alignment & padding

---

### **7. Structures & Unions**

* Defining structures
* Nested structures
* Array of structures
* Pointer to structure
* Self-referential structures (linked lists)
* Unions
* `typedef`, `using` (C++)

---

### **8. Enumerations & Macros**

* `enum` (C-style and `enum class` in C++)
* `#define` macros
* Conditional compilation
* Preprocessor directives
* `const`, `constexpr` (C++)

---

### **9. Object-Oriented Programming (C++)**

* Classes & objects
* Encapsulation
* Constructors & destructors
* Copy constructor & assignment operator
* Deep vs shallow copy
* Operator overloading
* Inheritance (single, multiple, multilevel, hybrid, hierarchical)
* Virtual functions & polymorphism
* Abstract classes & pure virtual functions
* Function overriding & hiding
* Friend functions & classes
* Static members
* `this` pointer
* Aggregation & Composition

---

### **10. Advanced OOP (C++)**

* Templates (function & class templates)
* Template specialization
* Variadic templates
* Namespaces
* Inline namespaces
* Modules (C++20+)
* PImpl idiom
* CRTP (Curiously Recurring Template Pattern)

---

### **11. Standard Template Library (STL)**

* Sequence containers: `vector`, `deque`, `list`, `array`, `forward_list`
* Associative containers: `set`, `multiset`, `map`, `multimap`
* Unordered containers: `unordered_set`, `unordered_map`
* Container adapters: `stack`, `queue`, `priority_queue`
* Iterators (input, output, forward, bidirectional, random access)
* Algorithms (`sort`, `find`, `accumulate`, etc.)
* Functors
* Lambdas & closures
* Allocators

---

### **12. Exception Handling**

* `try`, `catch`, `throw`
* Standard exceptions (`runtime_error`, `logic_error`, etc.)
* Custom exceptions
* `noexcept`

---

### **13. File Handling & Streams**

* `ifstream`, `ofstream`, `fstream`
* Text vs binary files
* Random access in files
* String streams (`stringstream`)
* Stream manipulators

---

### **14. Multithreading & Concurrency (C++11+)**

* `std::thread`
* `join`, `detach`
* Mutexes & locks (`std::mutex`, `std::unique_lock`)
* Deadlocks & prevention
* Condition variables
* Atomics (`std::atomic`)
* Futures & promises
* `std::async`

---

### **15. Advanced C++ Features**

* `auto` & type inference
* Range-based loops
* `nullptr`
* Uniform initialization
* Move semantics & rvalue references
* `decltype`, `typeid`
* `constexpr`
* Structured bindings (C++17)
* `std::optional`, `std::variant`, `std::any`
* Concepts & ranges (C++20)
* Coroutines (C++20)
* Reflection (future C++)

---

### **16. Low-Level C/C++**

* Function pointers & callbacks
* Bitwise operations & bit tricks
* Inline assembly
* Placement new
* Memory pools & custom allocators
* vtable & virtual dispatch
* ABI compatibility
* Interfacing with C libraries (`extern "C"`)

---

### **17. System-Level & Build Tools**

* Compilation process: preprocessing, compilation, assembling, linking
* Static vs dynamic linking
* Makefiles
* CMake basics
* Debugging tools: `gdb`, sanitizers, valgrind
* Cross-platform considerations

---

### **18. Design Patterns in C++**

* Singleton
* Factory & Abstract Factory
* Builder
* Prototype
* Observer
* Strategy
* Command
* RAII pattern
* Adapter, Proxy, Decorator
* PImpl idiom
* CRTP pattern

---

### **19. Data Structures & Algorithms in C/C++**

* Arrays, linked lists
* Stacks, queues, priority queues
* Hashing (maps, sets)
* Trees (binary, BST, AVL, Red-Black, B-trees)
* Graphs (adjacency list/matrix, BFS/DFS, shortest path)
* Searching & sorting algorithms
* Dynamic programming & greedy algorithms

---

### **20. Modern Applications**

* Socket programming (C/C++)
* Inter-process communication (IPC)
* Networking basics (TCP, UDP)
* Shared memory, pipes
* Game development basics with SDL/OpenGL
* Writing libraries
* Unit testing frameworks (GoogleTest, Catch2)
* Using Boost libraries

---


## **Qt, Win32 & RTOS Topics**

---

### **1. Qt Framework (C++ GUI & Application Development)**

#### **Basics**

* Introduction to Qt (cross-platform, signal-slot mechanism)
* Qt Creator IDE & project structure
* Qt core modules (`QtCore`, `QtGui`, `QtWidgets`)

#### **Core Concepts**

* Signals & Slots
* Event loop and event handling
* Layout management
* Widgets (QPushButton, QLabel, QLineEdit, QTableWidget, etc.)
* Dialogs (modal, non-modal, custom dialogs)
* Menus, toolbars, status bar

#### **Intermediate**

* Model/View architecture (`QTableView`, `QListView`, `QTreeView`)
* Qt Designer (drag-and-drop UI design)
* Resource system (`.qrc` files for images, icons)
* Multithreading in Qt (`QThread`, `QtConcurrent`)
* Networking (`QTcpSocket`, `QUdpSocket`, `QNetworkAccessManager`)
* File handling & serialization (`QFile`, `QDataStream`, JSON/XML handling)

#### **Advanced**

* Custom widgets & painting (`QPainter`)
* Styles & themes (QSS – Qt Style Sheets)
* MVC patterns in Qt
* Internationalization (i18n & l10n)
* Qt Quick / QML (for modern UIs)
* Integrating with databases (`QSqlDatabase`)
* Integrating C++ with QML
* Signals/slots with lambdas (modern Qt)
* Cross-platform deployment

---

### **2. Win32 API (Windows Programming in C/C++)**

#### **Basics**

* Windows architecture & subsystems
* WinMain vs main
* Message loop & event-driven programming
* Windows handles (HWND, HINSTANCE, HDC)
* Creating windows (`CreateWindow`, `RegisterClass`)
* GDI basics (drawing text, lines, shapes)

#### **Core Concepts**

* Message handling (`WM_PAINT`, `WM_SIZE`, `WM_DESTROY`, etc.)
* Dialog boxes (modal, modeless)
* Controls (buttons, edit boxes, list boxes, combo boxes)
* Menus, accelerators, resources (`.rc` files)
* Keyboard & mouse input
* Timers
* File I/O with Win32 API
* Dynamic link libraries (DLLs)

#### **Intermediate**

* Multithreading (CreateThread, synchronization objects like mutexes, semaphores, events)
* Memory management (VirtualAlloc, HeapAlloc)
* Windows registry programming
* COM basics
* Shell API (interacting with Explorer, file dialogs)

#### **Advanced**

* GDI+ (advanced graphics)
* Direct2D/Direct3D basics
* Windows sockets (Winsock)
* Interprocess communication (shared memory, named pipes)
* Hooking & subclassing windows
* Services programming
* WinRT/Modern Windows APIs (optional)

---

### **3. RTOS (Real-Time Operating Systems in C/C++)**

#### **Basics**

* What is an RTOS? (hard vs soft real-time, differences from general OS)
* RTOS kernel concepts
* Tasks/threads
* Task scheduling (preemptive, cooperative, round-robin, priority-based)

#### **Core Concepts**

* Task creation & management
* Context switching
* Synchronization primitives (semaphores, mutexes, event flags, message queues)
* Inter-task communication (pipes, mailboxes, shared memory)
* Interrupt handling
* Priority inversion & avoidance (priority inheritance, ceiling protocols)

#### **Intermediate**

* Memory management in RTOS (fixed-size block allocation, memory pools)
* Timer services
* Real-time clocks & tick interrupts
* Task states (ready, running, blocked, suspended)
* Deadlock detection & handling
* Device drivers in RTOS
* Power management in embedded RTOS

#### **Advanced**

* Multi-core scheduling in RTOS
* Real-time networking (RTOS + TCP/IP stack)
* Real-time file systems
* Safety-critical systems (MISRA C/C++ guidelines)
* RTOS case studies (FreeRTOS, VxWorks, QNX, RTEMS, Zephyr)
* RTOS performance tuning
* Debugging & profiling on RTOS (JTAG, SWO, trace tools)

---


