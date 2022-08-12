0x16. C - Simple Shell
Creating a simple shell

General

*Who designed and implemented the original Unix operating system
** Thompson and Dennis Ritchie created the first version of UNIX in 1969.
*Who wrote the first version of the UNIX shell
**Thomson shell, sh was the first UNIX shell and written by Ken Thompson
*Who invented the B programming language (the direct predecessor to the C programming language)
**B programming language was developed by Ken Thompson and Dennis Ritchie at Bell Labs
*Who is Ken Thompson
**He was a computer scientist who is known by his work in designing and developing origninal UNIX os.
*How does a shell work
**shell works Command-Line Interface which brought accebility fo OS as well as executing and invocking programs.
*What is a pid and a ppid
** PID Process ID,PPID Parent Process ID
*How to manipulate the environment of the current process
**if you need to communicate a change to a running process, the environment isn't good the rignt tool to perform it.
*What is the difference between a function and a system call
**A function call is a request to perform a task, while a system call is a request for the kernel to access a resource.
*How to create processes
**I UNIX and POSIX you call fork() and then exec()
*What are the three prototypes of main
**int main(), int argc, char **argv
*How does the shell use the PATH to find the programs
**it reads each directory one by one starting from the root directory through the current directory
*How to execute another program with the execve system call
**it is excuted if the file name isbinary executable or a writing starting wiht shebang.
*How to suspend the execution of a process until one of its children terminates
**it is suspended by the wiait() system call
*What is EOF / “end-of-file”?
**it means the file it was reading is inded.
