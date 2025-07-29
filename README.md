# Fix My Code Challenge - Holberton School

A unique debugging and code correction project where students dive into an existing codebase containing intentional bugs and fix them across multiple programming languages. This challenge develops critical debugging skills, code analysis abilities, and familiarity with legacy codebases.

## 📋 Description

**Fix My Code Challenge** - A debugging-focused project featuring:
- **Multi-language debugging** across C, Python, JavaScript, and Ruby
- **Real-world scenarios** with authentic code problems
- **Critical thinking** and problem-solving methodologies
- **Code analysis** and error identification techniques
- **Legacy codebase navigation** and understanding
- **Testing and validation** of fixes

## 👨‍💻 Author

**Yoruan Orta**
- GitHub: [@YoruanOrta](https://github.com/YoruanOrta)
- Project: Code Debugging and Problem Solving

## 🗂️ Project Structure

```
holbertonschool-Fix_My_Code_Challenge/
├── challenge/                  # Main challenge directory
│   ├── 4-delete_dnodeint/     # C - Doubly linked list deletion
│   │   ├── add_dnodeint_end.c  # Helper function for node addition
│   │   ├── delete_dnodeint     # Compiled executable
│   │   ├── delete_dnodeint_at_index.c # Main deletion function to fix
│   │   ├── free_dlistint.c     # Memory cleanup function
│   │   ├── lists.h             # Header file with structures
│   │   ├── main.c              # Test program
│   │   └── print_dlistint.c    # List printing utility
│   ├── 0-fizzbuzz.py          # Python - FizzBuzz implementation fix
│   ├── 1-print_square.js      # JavaScript - Square printing function
│   ├── 2-sort.rb              # Ruby - Sorting algorithm implementation
│   ├── 3-user.py              # Python - User class implementation
│   └── README.md              # Challenge-specific documentation
└── README.md                  # Main project documentation
```

## 🚀 Technology Stack

- **C (61.1%)** - Systems programming and data structures
- **Python (24.1%)** - Object-oriented programming and algorithms
- **JavaScript (7.6%)** - Frontend scripting and DOM manipulation
- **Ruby (7.3%)** - Scripting and algorithm implementation

## 🔧 Challenge Breakdown

### **Challenge 0: FizzBuzz Fix** (`0-fizzbuzz.py`)
- **Language**: Python
- **Problem**: Classic FizzBuzz algorithm with logical errors
- **Skills**: Conditional logic, modular arithmetic, algorithm implementation
- **Fix Required**: Correct the condition checking and output formatting

### **Challenge 1: Print Square** (`1-print_square.js`)
- **Language**: JavaScript
- **Problem**: Square pattern printing with formatting issues
- **Skills**: Loop construction, string manipulation, console output
- **Fix Required**: Correct the square drawing algorithm and formatting

### **Challenge 2: Sorting Algorithm** (`2-sort.rb`)
- **Language**: Ruby
- **Problem**: Sorting implementation with algorithmic errors
- **Skills**: Array manipulation, sorting algorithms, Ruby syntax
- **Fix Required**: Implement correct sorting logic and argument handling

### **Challenge 3: User Class** (`3-user.py`)
- **Language**: Python
- **Problem**: Object-oriented class implementation with method errors
- **Skills**: Class design, method implementation, Python OOP
- **Fix Required**: Correct class methods and attribute handling

### **Challenge 4: Doubly Linked List Deletion** (`4-delete_dnodeint/`)
- **Language**: C
- **Problem**: Complex data structure manipulation with memory management
- **Skills**: Pointer manipulation, memory management, linked list operations
- **Fix Required**: Correct node deletion logic and prevent memory leaks

## ⚙️ Setup and Usage

### Prerequisites
```bash
# C Compiler (GCC)
gcc --version

# Python 3
python3 --version

# Node.js for JavaScript
node --version

# Ruby interpreter
ruby --version
```

### Running Individual Challenges

#### **Python Challenges**
```bash
# FizzBuzz Challenge
cd challenge/
python3 0-fizzbuzz.py

# User Class Challenge
python3 3-user.py
```

#### **JavaScript Challenge**
```bash
# Print Square Challenge
cd challenge/
node 1-print_square.js
```

#### **Ruby Challenge**
```bash
# Sorting Challenge
cd challenge/
ruby 2-sort.rb
```

#### **C Challenge**
```bash
# Doubly Linked List Challenge
cd challenge/4-delete_dnodeint/
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o delete_dnodeint
./delete_dnodeint
```

### Testing and Validation
```bash
# Test each fixed implementation
cd challenge/

# Python tests
python3 -m pytest 0-fizzbuzz.py  # If test framework available
python3 3-user.py

# JavaScript tests
node 1-print_square.js

# Ruby tests
ruby 2-sort.rb arg1 arg2 arg3

# C tests with Valgrind (memory leak detection)
cd 4-delete_dnodeint/
valgrind --leak-check=full ./delete_dnodeint
```

## 🎯 Learning Objectives

By completing this challenge, I have developed:

### **Debugging Skills:**
- ✅ Systematic approach to identifying bugs and errors
- ✅ Code analysis and logical reasoning
- ✅ Understanding of common programming mistakes
- ✅ Error pattern recognition across multiple languages

### **Multi-Language Proficiency:**
- ✅ C programming with memory management
- ✅ Python object-oriented programming
- ✅ JavaScript functional programming
- ✅ Ruby scripting and algorithm implementation

### **Problem-Solving Methodology:**
- ✅ Reading and understanding existing codebases
- ✅ Identifying root causes of issues
- ✅ Implementing targeted fixes without breaking functionality
- ✅ Testing and validating solutions

### **Code Quality:**
- ✅ Memory management and leak prevention
- ✅ Proper error handling and edge cases
- ✅ Code readability and maintainability
- ✅ Best practices across different programming paradigms

## 🔍 Debugging Process

### **1. Code Analysis**
- Read and understand the existing codebase
- Identify the expected behavior vs. actual behavior
- Trace through the logic flow and data structures

### **2. Problem Identification**
- Use debugging tools (gdb, print statements, console.log)
- Identify specific lines or functions causing issues
- Understand the scope and impact of the bug

### **3. Solution Implementation**
- Implement minimal changes to fix the core issue
- Maintain original code structure when possible
- Ensure the fix doesn't introduce new bugs

### **4. Testing and Validation**
- Test with various inputs and edge cases
- Use memory checking tools for C programs
- Verify that all functionality works as expected

## 💡 Common Bug Patterns Fixed

### **Memory Management Issues (C)**
- Memory leaks from missing free() calls
- Segmentation faults from invalid pointer access
- Double free errors and dangling pointers

### **Logic Errors (Python/JavaScript/Ruby)**
- Off-by-one errors in loops
- Incorrect conditional statements
- Wrong variable assignments or comparisons

### **Algorithm Implementation**
- Incorrect sorting logic
- Boundary condition errors
- Missing or incorrect base cases

### **Object-Oriented Issues**
- Incorrect method definitions
- Missing or wrong attribute initialization
- Improper inheritance or encapsulation

## 🔧 Tools and Techniques Used

### **Debugging Tools**
- **GDB**: C program debugging and analysis
- **Valgrind**: Memory leak detection and analysis
- **Print Debugging**: Strategic output statements for logic tracing
- **IDE Debuggers**: Integrated debugging environments

### **Testing Strategies**
- **Unit Testing**: Individual function validation
- **Integration Testing**: Component interaction verification
- **Edge Case Testing**: Boundary condition analysis
- **Memory Testing**: Leak detection and pointer validation

### **Code Analysis**
- **Static Analysis**: Code review without execution
- **Dynamic Analysis**: Runtime behavior observation
- **Performance Analysis**: Efficiency and optimization review

## 🏆 Key Achievements

### **Multi-Language Debugging**
- Successfully debugged code in 4 different programming languages
- Demonstrated adaptability across different programming paradigms
- Applied language-specific debugging techniques effectively

### **Complex Problem Solving**
- Fixed intricate data structure manipulation bugs
- Resolved memory management issues in C
- Corrected algorithmic logic errors across multiple languages

### **Real-World Skills**
- Developed ability to work with legacy codebases
- Learned to make minimal, targeted fixes
- Gained experience with production-like debugging scenarios

## 📚 Skills Developed

### **Technical Skills**
- Advanced debugging techniques across multiple languages
- Memory management and pointer manipulation in C
- Object-oriented programming concepts in Python
- Functional programming patterns in JavaScript and Ruby

### **Analytical Skills**
- Code reading and comprehension
- Problem decomposition and analysis
- Root cause identification
- Solution design and implementation

### **Professional Skills**
- Working with existing codebases
- Code maintenance and legacy system support
- Documentation and communication of fixes
- Testing and quality assurance practices

## 🔄 Challenge Workflow

1. **Analyze**: Read and understand the broken code
2. **Identify**: Locate the specific bugs and issues
3. **Plan**: Design minimal fixes that address root causes
4. **Implement**: Apply fixes while preserving original functionality
5. **Test**: Validate fixes with comprehensive testing
6. **Document**: Record the problems found and solutions applied

## 👨‍💻 Author

**Yoruan Orta**
- GitHub: [@YoruanOrta](https://github.com/YoruanOrta)
- Repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/YoruanOrta/holbertonschool-Fix_My_Code_Challenge)
- Project: Holberton School Fix My Code Challenge

## 📄 License

This project is part of the Holberton School curriculum and is intended for educational purposes only.

---

⭐ **Holberton School** - Fix My Code Challenge | 2025

> *"The best debugger ever written is careful thought, coupled with judiciously placed print statements." - Brian Kernighan*
