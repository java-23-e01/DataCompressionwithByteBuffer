
### Exercise 6: Data Compression with ByteBuffer

**Time Estimate:** 60 minutes

**Description:** Create a Java program that reads data from a file, compresses it using a compression algorithm (e.g., GZIP), and writes the compressed data to another file using `ByteBuffer`.

**Guidelines:**

1. Read the contents of an input file (e.g., "input.txt") into a `ByteBuffer`.

2. Implement data compression (e.g., using `GZIPOutputStream`) on the data in the buffer.

3. Write the compressed data to an output file (e.g., "output.gz") using `ByteBuffer`.

4. Ensure proper exception handling and resource cleanup.


In this exercise, the program reads data from "input.txt," compresses it using GZIP compression, and writes the compressed data to "output.gz" using `ByteBuffer`. Make sure to have an "input.txt" file with data to compress before running the program.
