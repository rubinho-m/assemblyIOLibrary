# IO-library

### string_length
The function takes a pointer to a null-terminated string and returns its length by counting the number of characters until the null character \0.

### print_string
Takes a pointer to a null-terminated string and outputs it to standard output (stdout).

### print_char
The function takes a character code and outputs it to standard output (stdout).

### print_newline
Prints a newline character (code 0xA) to standard output (stdout).

### print_uint
Outputs an unsigned 8-byte integer in decimal format. It converts the number to a string and then uses print_string to print it.

### print_int
Outputs a signed 8-byte integer in decimal format. It checks the sign of the number and calls print_uint to print the absolute value with the appropriate sign.

### string_equals
Takes two pointers to null-terminated strings and compares them. If the strings are equal, the function returns 1; otherwise, it returns 0.

### read_char
Reads a single character from standard input (stdin) and returns it. It returns 0 if the end of the stream is reached.

### read_word
Reads a word from standard input (stdin), skipping leading spaces and whitespace characters. It returns a pointer to the read word and its length.

### parse_uint
Takes a pointer to a string and attempts to read an unsigned number from the beginning. It returns the number and its length in characters.

### parse_int
Takes a pointer to a string and attempts to read a signed number from the beginning. It returns the number and its length in characters.

### string_copy
Takes a pointer to a string, a pointer to a buffer, and the buffer's length. It copies the string into the buffer and returns the length of the copied string if it fits in the buffer; otherwise, it returns 0.
