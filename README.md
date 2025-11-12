Huffman Coding for Text File Compression

Developed a file compression and decompression system using Huffman Coding, a lossless, bottom-up compression algorithm widely used in information theory. The program efficiently compresses and restores text files without data loss.

Key Features:

Encode: Compresses input text files by generating Huffman codes based on character frequency.

Decode: Decompresses encoded files back to their original form.

Implementation Overview:

Utilized a Node structure to represent Huffman Tree nodes, storing character data, frequency, and binary codes.

Designed a Huffman class with core methods — compress() and decompress() — and a constructor for input/output file handling.

Implemented the following key steps:

createMinHeap(): Builds a frequency map of characters and constructs a min-heap using a priority queue.

createTree(): Generates the Huffman Tree by combining nodes with the lowest frequencies until one root remains.

createCodes(): Traverses the Huffman Tree to assign binary codes to each character.

saveEncodedFile(): Writes the compressed binary data into the output file.

Demo:

<img width="998" height="228" alt="image" src="https://github.com/user-attachments/assets/851f7e7e-bd21-4736-9d2c-556eb60763a2" />

Before compression:

<img width="576" height="639" alt="image" src="https://github.com/user-attachments/assets/237230c9-b329-4ed5-96be-4c9ab099cc42" />

Compressed File:

<img width="579" height="665" alt="image" src="https://github.com/user-attachments/assets/b742e24d-a4cb-4474-b3e0-1ffd3bbe6a1d" />

Decompressed File:

<img width="562" height="640" alt="image" src="https://github.com/user-attachments/assets/e624d1a9-0698-478e-9418-05d37ae88d92" />



