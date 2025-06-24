- Previously, we've assumed that the code will run to completion or the debugging methods will not work
- Modern IDEs come with integrated tool called a debugger so the code itself doesn't need to complete to debug
# Stepping
- **debugger** - Program that allows the programmer to control how another program executes and examines the program while running
- **Stepping** - Set of related debugger features that let us execute our code statement by statement
### Step into and step over 
- **Step into** - Command that executes the next statement in the normal execution path of the program, the pauses execution to examine the program's state using the debugger
- **step over** - similar to step into but when a function is called, it executes the whole function at once whereas step into executes lines of the called function one by one
- Consider:
``` cpp
#include <iostream>
void printValue(int value)
{
	std::cout << value << '\n';
}
int main()
{
	printValue(5)
	return 0;
}
```

- With step into, when `printValue` is called, the debugger will check every line in the `printValue` function
- With step over, when `printValue` is called, the debugger will simply execute the function
- Note that step into will step into anything, in this case, the debugger will step into the function `std::cout`
#### Run to cursor
-  command executes the program until execution reaches the statement selected by your cursor.
- In VS code, choose a break point, debug, right click and run to cursor
#### Continue 
- **Continue** - debug command that simply continues running either until the program terminates or something triggers control to return back to you.
#### Start
- Just like continue but it does that from the start of the program
	- It can only be invoked when not already in a debug session
#### Breakpoints
- **Breakpoints** - special marker that tells the debugger to stop execution of the program at the breakpoint when running in debug mode
### Watching variables
- **watching variable** - process of inspecting the value of a variable while the program is executing in debug mode
### The call stack
- When a program calls a function, it bookmakrs the current location, makes the function call, and then returns
- **Call stack** - list of all the active functions that have been called to get to the current point of execution
- Includes:
	- Entry for each function called
	- which line of code will be returned to when the function is called
- When a new function is called, that function is added to the top of the call stack, when it returns to the caller, it is removed from the top of the call stack and control returns to the function below it.
- **Call stack window** - shows the current call stack
- 