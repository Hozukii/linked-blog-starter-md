## Debugging tactics
### 1 - commenting out code
- If there is a function we wouldn't know what is causing the issue, then just comment it out and see if error even goes out in the first place
- 3 likely outcomes
	- The error goes away
	- The problem is unchanged
	- commenting out the function creates new error indicating that the program is dependent on it, then we wouldn't be able to tell if the issue stems from the function
### 2 - Validating your code flow
- It can be the case that a function is being called too many or too few times
- It can be helpful to add a statement to the top of the function to see every time it's being called
- When debugging use `std::cerr` instead of `std::out` as `std::out` has some buffer from when it's called to when it outputs
### 3 - Printing values
Example:
``` cpp 
#include <iostream>
int add(int x, int y)
{
std::cerr << "add() called (x=" << x <<", y=" << y << ")\n";
	return x + y;
}

void printResult(int z)
{
	std::cout << "The answer is: " << z << '\n';
}

int getUserInput()
{
	std::cout << "Enter a number: ";
	int x{};
	std::cin >> x;
	return x;
}

int main()
{
	int x{ getUserInput() };
std::cerr << "main::x = " << x << '\n';
	int y{ getUserInput() };
std::cerr << "main::y = " << y << '\n';

	int z{ add(x, 5) };
std::cerr << "main::z = " << z << '\n';
	printResult(z);

	return 0;
}
```

### Using a logger 
- **Log** - sequential records of events that have happened, usually time stamped
- It's advantageous as output does not have to be changed as the log is on a separate file
- C++ contains output stream named `std::clog` but it's recommended to use a third party tools (e.g. plog)
- 