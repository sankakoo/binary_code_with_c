# Printing Hello World in C and Converting to Binary

This is a simple project that demonstrates how to print "Hello, World!" in the C programming language and then convert it into binary code.

## Prerequisites

Before you begin, ensure that you have the following installed on your system:

- C compiler (e.g., GCC)
- Text editor or integrated development environment (IDE)

## Instructions

Follow these steps to run the program:

1. Open a text editor or IDE and create a new C file (e.g., `hello.c`).
2. Copy and paste the following code into the file:

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

3. Save the file.

4. Open a terminal or command prompt and navigate to the directory where you saved the file.

5. Compile the C code by running the following command:

```
make hello
```

6. If there are no errors, run the program by executing the following command:

```
./hello
```

7. You should see the output `Hello, World!` printed to the console.

8. To convert the C code into binary, you can use a tool like `objdump`. Run the following command:

```
xxd -b hello | cut -d ' ' -f 2-7 | tr -d ' \n'
```

9. The output will include the binary representation of the compiled code.

## Conclusion

Congratulations! You have successfully written a C program to print "Hello, World!" and converted it into binary code. This project serves as a basic introduction to C programming and binary representation.

Feel free to explore further and modify the code to experiment with different outputs or add more functionality.
