# Project: Custom Printf Implementation

## Overview
This is a specialized printf function in C, blending functionality with style. 
This implementation follows strict guidelines and leverages the power of the printf function, offering a unique take on string 
formatting in the C programming language.

## Features
- **Efficient Implementation**: Carefully designed and optimized for performance.
- **Adherence to Standards**: The code strictly follows the Betty style and meets the requirements specified in the project guidelines.
- **Dynamic Memory Handling**: Utilizes malloc and free for efficient memory management.
- **Variadic Arguments**: Harnesses the power of va_start, va_end, va_copy, and va_arg for handling variable arguments.

## Getting Started
Follow these steps to incorporate my custom printf function into your C projects:

1. Clone this repository to your local machine.
2. Include the main.h header file in your project.
3. Call the `_printf` function with the desired format string and arguments.

```c
#include "main.h"

int main(void) {
    _printf("Hello, %s!\n", "World");
    return 0;
}

