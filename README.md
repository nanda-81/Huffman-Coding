## Project Overview

This project demonstrates **file compression and decompression** using the **Huffman Coding algorithm**. Huffman Coding is an efficient method for encoding data using variable-length binary codes based on the frequency of characters. This C++ implementation compresses text files into `.huf` format and decompresses them back into readable `.txt` files.

### Features:

- **File Compression**: Compresses a text file using Huffman coding, reducing the file size by assigning shorter binary codes to frequently occurring characters.
- **File Decompression**: Decompresses a `.huf` file back into its original text form.

## Project Structure

- **`encode.cpp`**: Handles file compression.
- **`huffman.cpp`**: Handles file the code and implementation of both.
- **`decode.cpp`**: Handles file decompression.
- **`input.txt`**: A sample input text file used for testing.
- **`compressed.huf`**: The output file after compression.
- **`output.txt`**: The file generated after decompression.

## COMPRESSION

Opened the terminal and ran this command to compress `.txt` file to `.huf` file 

```cpp
PS C:\Documents\Huffman Coding Project\Huffman Coding> g++ encode.cpp huffman.cpp -o main
PS C:\Documents\Huffman Coding Project\Huffman Coding> ./main inputFile.txt compressedFile.huf
Compressed successfully
PS C:\Documents\Huffman Coding Project\Huffman Coding>
```

The difference in the file size can be noticed.

![Compression Screenshot](https://github.com/user-attachments/assets/d02aa394-c021-4f1d-aa7f-6b1dadf57eb7)

![Compressed file location](https://github.com/nanda-81/Huffman-Coding/blob/main/Screenshot%20(147).png)

## DECOMPRESSION

Opened the terminal and ran this command to decompress the `.huf` file to `.txt` file .

```cpp
PS C:\Documents\Huffman Coding Project\Huffman Coding> g++ decode.cpp huffman.cpp -o main
PS C:\Documents\Huffman Coding Project\Huffman Coding> ./main compressedFile.huf outputFile.txt
Decompressed successfully
PS C:\Documents\Huffman Coding Project\Huffman Coding>
```

The changes can be noticed.

![Decompression Screenshot](https://github.com/nanda-81/Huffman-Coding/blob/main/Screenshot%20(148).png)

![Output file location](https://github.com/nanda-81/Huffman-Coding/blob/main/Screenshot%20(149).png)
