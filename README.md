# C++ Systems Toolkit

## Project Goal

A personal C++ project focused on building practical systems programming utilities using modern C++.

The project aims to demonstrate:
- Modern C++ programming and STL usage
- File and directory operations
- Input validation and error handling
- Modular design and maintainable code
- Unit testing and build automation

## Planned Modules

1. Log Analyzer — analyze synthetic log files and summarize errors and warnings.
2. File System Utility — inspect directories and filter files.
3. Configuration Parser — parse and validate a simple configuration format.
4. Automated Tests — verify expected behavior and edge cases.

## Technology Stack

- C++
- CMake
- GoogleTest (planned)
- Git and GitHub

## Status

Currently under development. Modules will be added incrementally, with tests and documentation.


## 1. Problem

Developing reliable systems software requires more than writing code that works for normal inputs. Programs must handle malformed input, file operations, errors, and edge cases while remaining maintainable and testable.

This project aims to build a collection of independent C++ utilities to practice modern C++, systems programming fundamentals, defensive programming, and automated testing.

All examples and test data will be created independently for this project.

## 2. Planned Features

- **Log Analyzer:** Read synthetic log files and summarize errors, warnings, and informational messages.
- **File System Utility:** List files, filter by extension, and report file sizes.
- **Configuration Parser:** Parse a simple configuration format and validate its contents.
- **Error Handling:** Handle invalid inputs, missing files, and file access errors.
- **Modular Design:** Separate implementation, interfaces, and application entry points.
- **Automated Testing:** Test normal behavior, invalid inputs, and edge cases.

Features will be implemented incrementally.

## 3. Build Requirements

- **Language standard:** C++23
- **Compiler:** A C++ compiler with sufficient C++23 support, such as a recent GCC, Clang, or MSVC release.
- **Build system:** CMake 3.20 or later.
- **Version control:** Git.
- **Testing framework:** GoogleTest (planned).

The project will target C++23 and document the compiler versions used for development and testing. Compiler-specific requirements will be updated as features and dependencies are introduced.

## 4. How to Run

After the initial implementation and CMake setup are complete, the intended workflow will be:

1. Clone the repository.
2. Configure the project using CMake.
3. Build the executable.
4. Run the utility with a sample input file.

Example commands for the planned CMake build:

```bash
git clone <your-repository-url>
cd cpp-systems-toolkit
cmake -S . -B build
cmake --build build
```

These commands will become executable once the corresponding CMake configuration and source files have been added.

## 5. Tests

The project will include automated tests for:

- Valid inputs and expected outputs
- Empty or malformed input
- Missing files and file access errors
- Boundary conditions and edge cases
- Regression cases for previously fixed defects

GoogleTest is planned for unit testing. Test commands and coverage information will be documented after the test infrastructure is implemented.

## 6. Roadmap

- [ ] Initialize the project structure and CMake configuration.
- [ ] Implement the Log Analyzer.
- [ ] Add unit tests for the Log Analyzer.
- [ ] Implement the File System Utility.
- [ ] Implement the Configuration Parser.
- [ ] Add validation and error-handling tests.
- [ ] Add build and test instructions.
- [ ] Review code quality, documentation, and repository hygiene.

## Project Principles

- Use independently written code and synthetic test data.
- Prefer readable, maintainable C++ and clear interfaces.
- Validate inputs and handle errors explicitly.
- Keep the project free of employer-owned code, confidential data, credentials, and internal implementation details.


## Disclaimer

This is an independent learning project. It does not contain employer-owned source code, proprietary data, confidential logs, or internal implementation details.


