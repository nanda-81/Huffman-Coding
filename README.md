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

![Screenshot (150).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b8454294-17bd-4976-a23d-04457ec0e2e3/c395ff13-f4d5-417a-b5b8-1552b35ed7b2/Screenshot_(150).png)

![Screenshot (147).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b8454294-17bd-4976-a23d-04457ec0e2e3/4ac55499-00c6-47f1-9c07-b8647afcfb63/Screenshot_(147).png)

## DECOMPRESSION

Opened the terminal and ran this command to decompress the `.huf` file to `.txt` file .

```cpp
PS C:\Documents\Huffman Coding Project\Huffman Coding> g++ decode.cpp huffman.cpp -o main
PS C:\Documents\Huffman Coding Project\Huffman Coding> ./main compressedFile.huf outputFile.txt
Decompressed successfully
PS C:\Documents\Huffman Coding Project\Huffman Coding>
```

The changes can be noticed.

![Screenshot (148).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b8454294-17bd-4976-a23d-04457ec0e2e3/702927ea-6a4d-4c3d-b578-c31f850461f4/Screenshot_(148).png)

![Screenshot (149).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/b8454294-17bd-4976-a23d-04457ec0e2e3/3c403609-1a20-4019-807a-f3cb40348d4d/Screenshot_(149).png)
