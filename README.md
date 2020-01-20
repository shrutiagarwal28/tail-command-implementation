# tail-command-implementation

Implementing Tail Command on XV6

The traditional UNIX tail utility  can print out lines from end of a file. If the number of lines is not configured, tail would print out the last 10 lines of its input. Or it can be triggered by calling tail -NUM FILE.

We write a tail program. If a filename is provided on the command line then tail should open it, read and print the last NUM lines (no extra black lines), and then close it. If no filename is provided, tail should read from standard input.

 
