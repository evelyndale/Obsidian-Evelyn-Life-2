An application's memory contains space for:
	- Code (text)
	- Static/Global data
	- Stack
	- Heap (aka *free pool* or *free store* of memory or *dynamic memory*)
	
- **Stack Frame**: A block of memory allocated for a function or bit of code.
- Only make global variables if you need to, otherwise it's a waste of memory since they stay in the global memory storage for the lifetime of the code instead of clearing in the stack call after being used.
- Stack has a fixed size.
- Heap has variable size, aka *dynamic memory allocation*.
- Heap in memory is not the same thing as the heap data structure!.

[[C]] uses the functions:
	malloc
	calloc
	realloc
	free
	
[[C++]] uses the functions:
	new
	delete
