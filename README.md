# palindrome
A palindrome detector in both C and assembly

C code is structured in such a way to ease the translation to assembly
Testing for the C code is implemented with Unity

Constraints:
Input must be atleast two characters long.
    Only valid characters are [0-9A-Za-z] and white space
    Whitespaces are to be ignored
    A palindrome is to deisply on JTAG UART, "Palindrome detected"
        whlie lighting the five right most red LEDs
    Not a palindrome is to display just that, whlie lighting the
        five left most red LEDs
    Invalid user entry shall provide an error message

Assembly code is tested using:
    https://cpulator.01xz.ne
    ARMv7 on DE1 SOC
