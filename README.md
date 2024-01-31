printf with myself with no one 
int printf ( const char * format, ... );

This function is part of the standard library **<cstdio>** and to use it we must specify the header file **<stdio.h>**.

Writes the C string pointed by format to the standard output **(stdout)**. If format includes format specifiers (subsequences beginning with **%**), the additional arguments following format are formatted and inserted in the resulting string replacing their respective specifiers.
### Parameters
 > **format** -> C string that contains the text to be written to stdout.
 
Where the specifier character at the end is the most significant component, since it defines the type and the interpretation of its corresponding argument:
 Specifier | Output | Example
------------ | ------------- |-----------
 c | Character | A
 s | String of characters | Holberton
 % | A % followed by another % character will write a single % to the stream| %
  i and d | Signed decimal integer | 98 
 b | Unsigned binary | 10101
 u | Unsigned decimal integer | 98
 o | Unsigned octal | 5523
 x | Unsigned hexadecimal integer (lowercase) | 36264eb
 X | Unsigned hexadecimal integer (uppercase) | 36264EB
 r | Reversed string | gnirts |
 R | Rot13 string | cevags
##### Return Value.
On **success**, the **total number** of characters written is returned.
If a writing error occurs, the error indicator (ferror) is set and a negative number is returned.
 
## The tasks.
-[x] **I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life.** 
Write a function that produces output according to a format.

