# C++ Data Structures Coursework

C++ pointer, dynamic-memory, recursion, sorting, linked-list, tree and hash-map coursework.

## Contents

| Folder | Course/Lab | Topic | Language/Platform |
| --- | --- | --- | --- |
| `Lab4Assignment1` | Existing archived exercises | Menu-driven student list with append, count, display, and removal operations. | C / C++ |
| `ex2` | Existing archived exercises | Multiplies two fixed integers through pointers. | C / C++ |
| `ex3` | Existing archived exercises | Swaps two integers using pointer parameters. | C / C++ |
| `ex4` | Existing archived exercises | Counts characters by walking a null-terminated buffer. | C / C++ |
| `lab2ex1` | Existing archived exercises | Populates and prints a small fixed array of student records. | C / C++ |
| `turotial3ex7` | Existing archived exercises | Allocates integers individually and reads/prints/releases them. | C / C++ |
| `BinarySearchTreeLab10` | Existing archived exercises | Implements recursive BST insertion, traversals and height measurement. | C / C++ |
| `HashMap2` | Existing archived exercises | Bucket-chain hash map supports sign-up/login, table resizing and map display. | C / C++ |
| `RevisionEx4` | Existing archived exercises | Prints the first entered number of Fibonacci values using recursion. | C / C++ |
| `Revision1` | Existing archived exercises | Reads and multiplies two integers. | C / C++ |
| `Revision2` | Existing archived exercises | Reads an integer and reports odd/even. | C / C++ |
| `Revision3` | Existing archived exercises | Displays locally swapped values for two entered integers. | C / C++ |
| `Revision4` | Existing archived exercises | Reverses a fixed array in place and prints it. | C / C++ |
| `Tutorial3` | Existing archived exercises | Allocates, fills, prints and releases an integer array. | C / C++ |
| `tutorial3ex2` | Existing archived exercises | Returns a dynamically allocated/populated array and releases it in main. | C / C++ |
| `tutorial3ex4` | Existing archived exercises | Counts even values in a fixed integer array via a pointer. | C / C++ |
| `Tutorial-03-Maximum-Pointer` | Existing archived exercises | Returns a pointer to the largest double in an array. The included `tutorial3ex5.cpp` is the corrected historical archive member. | C / C++ |
| `tutorialex6` | Existing archived exercises | Reads and updates an integer through a pointer to a pointer. | C / C++ |
| `lab3ex1` | Existing archived exercises | Sorts a fixed integer array in descending order and prints it. | C / C++ |
| `revisionEx3` | Existing archived exercises | Computes greatest common divisor of positive integers by recursive subtraction. | C / C++ |
| `acsc183/Files2` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/FilesLab` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/HomeExam2` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/Lab4` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/Lab4Ex3` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/Lab5Ex1` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/Lab5Ex2` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `acsc183/revex3` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Ex1b` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Ex2b` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Ex3b` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Exercise1` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Exercise2` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Exercise3` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Lab2Exercise4` | Additional Mac/USB coursework | See detailed contents below | C++ |
| `first-year-intro/Rev3b` | Additional Mac/USB coursework | See detailed contents below | C++ |

Each folder is an independent exercise or project. Original names, source, dependency versions and required project configuration are preserved.

## Getting Started

Open an individual `.sln` in Visual Studio with the Desktop development with C++ workload. Each program is independent; build and run its own solution. The maximum-pointer exercise was copied unchanged from the corrected archive member and can be compiled directly with a C++ compiler. Some programs use Windows `system("pause")`. These are educational implementations; boundary/memory behavior and the hash-map login exercise are not production authentication.

## Validation

Lightweight local checks: MSVC 14.44 C++ compilation. Compiled programs were not executed; interactive behavior and memory correctness remain unverified.

## Notes

Original implementation is preserved. Build outputs, dependencies, machine-specific IDE state, backups, submission documents and private runtime data are excluded. No license has been inferred for the original work.

## Additional introductory and ACSC183 coursework

USB source-only additions cover file processing, strings and introductory arithmetic. ACSC183 context is supported by the parent/course material; the exact module of `first-year-intro` is not established. Each file has its own `main` and must be compiled separately.

| Folder | Course/Lab | Topic | Language/Platform |
| --- | --- | --- | --- |
| `acsc183/Files2` | ACSC183 / Files | Account master/transaction merge | C++ / file streams |
| `acsc183/FilesLab` | ACSC183 / Files | Write number pairs and sums/averages | C++ |
| `acsc183/HomeExam2` | ACSC183 / Home exam | Compare string lengths with a twenty-character bound | C++ / C strings |
| `acsc183/Lab4` | ACSC183 / Lab 4 | Reverse file lines and retain longest line | C++ / MSVC secure CRT |
| `acsc183/Lab4Ex3` | ACSC183 / Lab 4 | Name and birth-year comparisons | C++ |
| `acsc183/Lab5Ex1` | ACSC183 / Lab 5 | Sentence and character statistics | C++ |
| `acsc183/Lab5Ex2` | ACSC183 / Lab 5 | Two-word text search/highlighting | C++ |
| `acsc183/revex3` | ACSC183 / Revision | Numeric file min/max/average | C++ |
| `first-year-intro/Rev3b` | First year / Revision | Ten-character input, case counts and sorting | C++ / Windows console |
| `first-year-intro/Lab2Ex1b`, `Lab2Ex2b`, `Lab2Ex3b` | First year / Lab 2 | Introductory arithmetic and geometry | C++ |
| `first-year-intro/Lab2Exercise1`–`Lab2Exercise4` | First year / Lab 2 | Time, cost, real-number arithmetic and formatting | C++ |

Build a selected added file with Visual Studio's C++ developer prompt, for example `cl /EHsc acsc183\revex3\revex3.cpp`. Added source does not require the old IDE solutions. Portable exercises can also use `c++ -std=c++17 path/to/file.cpp -o exercise`. Lab4 uses `strcpy_s`, requiring MSVC's secure CRT; it does not compile unchanged with macOS Clang. Several programs call Windows `pause` or `cls`; use Windows for their intended console behavior. In Rev3b, read the characters before choosing count/sort/display.

File inputs belong in the executable's working directory and are deliberately not populated with private source datasets. Create your own small synthetic fixtures:

- Files2: `oldmast.txt` rows are `accountNumber customerId currentBalance`; `trans.txt` rows are matching `accountNumber amount` in the same order. Also pre-create an empty `newmast.txt`, because the unchanged program opens it as a default read/write fstream rather than a creating output stream.
- Lab4: `input.txt` with short text lines.
- Lab5Ex1: `CyprusNews.txt` with sentences containing periods; an input without sentence delimiters can divide by zero.
- Lab5Ex2: `CyprusNews.txt` with disposable text, then enter two search words. Historical matching/highlighting edge cases are unverified.
- revex3: `data.txt` with whitespace-separated numbers.
- FilesLab creates/truncates `out.txt` and `in.txt`; enter pairs, then a nonnumeric character to stop.

Mac validation: the added C++ sources passed syntax checks except the documented MSVC-only `strcpy_s` dependency. None was run; file, boundary and console behavior remains unverified. Existing coursework files are preserved.
