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
