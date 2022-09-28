

From the Yale course:
help

Get a description of gdb’s commands.

run

Runs your program. You can give it arguments that get passed in to your program just as if you had typed them to the shell. Also used to restart your program from the beginning if it is already running.

quit

Leave gdb, killing your program if necessary.

break

Set a breakpoint, which is a place where gdb will automatically stop your program. Some examples: - `break somefunction` stops before executing the first line `somefunction`. - `break 117` stops before executing line number 117.

list

Show part of your source file with line numbers (handy for figuring out where to put breakpoints). Examples: - `list somefunc` lists all lines of `somefunc`. - `list 117-123` lists lines 117 through 123.

next

Execute the next line of the program, including completing any procedure calls in that line.

step

Execute the next step of the program, which is either the next line if it contains no procedure calls, or the entry into the called procedure.

finish

Continue until you get out of the current procedure (or hit a breakpoint). Useful for getting out of something you stepped into that you didn’t want to step into.

cont

(Or `continue`). Continue until (a) the end of the program, (b) a fatal error like a Segmentation Fault or Bus Error, or (c) a breakpoint. If you give it a numeric argument (e.g., `cont 1000`) it will skip over that many breakpoints before stopping.

print

Print the value of some expression, e.g. `print i`.

display

Like `print`, but runs automatically every time the program stops. Useful for watching values that change often.

backtrace

Show all the function calls on the stack, with arguments. Can be abbreviated as `bt`. Do `bt full` if you also want to see local variables in each function.

set disable-randomization off

Not something you will need every day, but you should try this before running your program if it is producing segmentation faults outside of `gdb` but not inside. Normally the Linux kernel randomizes the position of bits of your program before running it, to make its response to buffer overflow attacks less predictable. By default, `gdb` turns this off so that the behavior of your program is consistent from one execution to the next. But sometimes this means that a pointer that had been bad with address randomization (causing a segmentation fault) turns out not to be bad without. This option will restore the standard behavior outside `gdb` and give you some hope of finding what went wrong.