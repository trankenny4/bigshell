# bigshell


BigShell Specification:
- Parse command-line input into commands to be executed
- Execute a variety of external commands (programs) as separate processes
- Implement a variety of shell built-in commands within the shell itself
- Perform a variety of i/o redirection on behalf of commands to be executed
- Assign, evaluate, and export to the environment, shell variables
- Implement signal handling appropriate for a shell and executed commands
- Manage processes and pipelines of processes using job control concepts

Learning Outcomes:
- Describe the Unix process API
- Write programs using the Unix process API (Module 3, MLO 3)
- Explain the concept of signals and their uses (Module 3, MLO 2)
- Write programs using the Unix API for signal handling (Module 3, MLO 3)
- Explain I/O redirection and write programs that can employ I/O redirection (Module 3, MLO 4)

Implements a large subset of the POSIX Shell’s functionality.

The high-level functionalities you will be tasked with implementing are:
- cd – Change the working directory
- exit – Cause the shell to exit
- unset – unset values of variables
- Signal handling behavior of the shell, and commands
- Command execution

- Expansion of Command words and assignment values
- Redirection filename operands
- I/O Redirection
- Variable assignment
- Simple foreground and background commands
- Shell pipeline
- Job control
