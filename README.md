# CS50
Introduction to Computer Science

Week 0: Scratch

Week 1: C

 GUI (Graphical User Interface):
 A GUI is a type of user interface that allows users to interact with a computer system or software through graphical elements such as windows, icons, buttons, menus, and other visual components. It is designed to be user- 
 friendly and intuitive, often requiring minimal technical knowledge.

 Example: Operating systems like Windows and macOS, or applications like web browsers and photo editors.

CL (Command Line):
  A CL (Command Line) or Command-Line Interface (CLI) is a text-based user interface that allows users to interact with a computer system or software by typing commands into a terminal or console. It is more efficient for 
  advanced users but requires familiarity with specific commands and syntax.

  Example: Terminal on Linux/macOS or Command Prompt/PowerShell on Windows.

In the terminal window, some common command-line arguments we may use include:
 cd, for changing our current directory (folder)
 cp, for copying files and directories
 ls, for listing files in a directory
 mkdir, for making a directory
 mv, for moving (renaming) files and directories
 rm, for removing (deleting) files
 rmdir, for removing (deleting) directories

Types
printf allows for many format codes. Here is a non-comprehensive list of ones you may utilize in this course:

%c = Represents a single character

%f = Represents a floating-point number (e.g., float).

%i/%d = Represents an integer (same as %d).

%li = Represents a long integer.

%s = Represents a string (null-terminated character array).

Week 2: ARRAY


Compiling a program involves four major steps:

1. Preprocessing

The preprocessor handles directives that begin with #, such as #include, #define, and conditional compilation (#ifdef, #ifndef, etc.).
It expands macros, includes header files, and processes conditional compilation statements.
The result is a pure source code file with all preprocessor directives replaced.

2. Compilation

The compiler translates the preprocessed source code into assembly language, a low-level representation of the program.
It checks for syntax errors and ensures the code follows language rules.
If errors exist, they must be corrected before proceeding.

3. Assembly

The assembler converts the assembly code into machine code (binary instructions) that the CPU can execute.
The output is an object file (.o or .obj), containing machine code but still missing links to external functions and libraries.

4. Linking

The linker takes one or more object files and combines them into an executable program.
It resolves references to external libraries, functions, and global variables.
If there are missing dependencies or unresolved symbols, linking errors occur.
