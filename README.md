# Libft

A custom C library developed during the 42 Berlin Core Curriculum.

The goal of this project was to recreate commonly used functions from the C standard library while gaining a deeper understanding of C, memory management, pointers, and data structures.

The library includes the mandatory Libft functions, bonus linked-list utilities, and additional helper functions added during my development work.

## Features

### Libc Reimplementations

Custom implementations of common functions:

* Character checks
* String manipulation
* Memory operations
* Conversion functions
* File descriptor output

### Bonus Part

Linked-list utilities:

* Creating nodes
* Adding/removing elements
* Iterating over lists
* Mapping list contents
* Cleaning allocated memory

### Additional Helpers

Extra utilities added during the 42 curriculum, including:

* `get_next_line` related functions
* Additional helper functions

## Build

```bash
make
```

Builds the static library:

```bash
libft.a
```

With bonus functions:

```bash
make bonus
```

Clean:

```bash
make clean
make fclean
```
Clean and recompile:

```bash
make re
```

## Usage

Include the header:

```c
#include "libft.h"
```

Compile with:

```bash
cc main.c -L. -lft -o program
```

## Skills Practiced

* C programming
* Pointers
* Memory management
* Dynamic allocation
* String handling
* Linked lists
* Static libraries
* Makefiles

## Author

beXxou

42 Berlin

