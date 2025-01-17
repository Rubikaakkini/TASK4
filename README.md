# TASK4
COMPANY CODETECH IT SOLUTIONS
NAME : Rubika A 
INTERN ID : CT08HCQ
**DOMAIN NAME ** : C Programming 
**BATCH DURATION **: December 30th, 2024 to January 30th, 2025 
MENTOR NAME : Neela Santhosh Kumar

Description of the Program
This program implements a basic Run-Length Encoding (RLE) algorithm, a simple and efficient compression method. It reads a text file, compresses or decompresses its content, and saves the output to another file.

Features of the Program
Compression:

Groups consecutive occurrences of a character and replaces them with the character followed by the count.
Example: AAABBBCCDAA → A3B3C2D1A2.
Function: compressFile.
Decompression:

Reads compressed input and expands it back to its original form.
Example: A3B3C2D1A2 → AAABBBCCDAA.
Function: decompressFile.
Menu-Driven Interface:

Allows users to choose between compression and decompression.
Exit option is available.
How to Compile and Run
Save the program as rle_tool.c.
Compile the code:
bash
Copy
Edit
gcc rle_tool.c -o rle_tool
Run the tool:
bash
Copy
Edit
./rle_tool
Example Usage
Input File: input.txt
plaintext
Copy
Edit
AAAABBBCCDAA
Compression Process:
plaintext
Copy
Edit
Enter the name of the input file to compress: input.txt
Enter the name of the output compressed file: compressed.txt
File compressed successfully to compressed.txt.
Compressed Output File: compressed.txt
plaintext
Copy
Edit
A4B3C2D1A2
Decompression Process:
plaintext
Copy
Edit
Enter the name of the compressed file to decompress: compressed.txt
Enter the name of the output decompressed file: decompressed.txt
File decompressed successfully to decompressed.txt.
Decompressed Output File: decompressed.txt
plaintext
Copy
Edit
AAAABBBCCDAA

**THE OUTPUT OF THE FILE

![Image](https://github.com/user-attachments/assets/5852e1ab-3cae-4691-90ca-0b8b99aaa8d5)
