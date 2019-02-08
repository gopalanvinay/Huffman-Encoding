# Basic Text Compression using Huffman Encoding


The Encoder uses BitIO's functionality to read characters from files and uses Huffman to determine how the
characters should be encoded. It then accesses a .comp file and writes into the file.
Decode reverses the process and writes into a .comp.plaintext file. 

files (name, raw size, compressed size):
	1. bee_movie, 55,339, 32,307
	2. id_ascii, 11,791, 5,505
	3. ascii_arts, 11,077, 4,510
	4. huffman_homework_description, 9,645, 5,926
	5. bible_new, 3,880,246, 2,222,159	

This build is still under progress. It is slow because we compute a new Huffman Tree for each new letter inserted. A cached version would be much faster.

To run and build this project on your machine:
  1. Clone this repository on to your local machine.
  2. Enter the “huffman-encoding” directory.
  3. Run ”make”. The Makefile will compile the necessary .cc files.
  4. Run “./encoder file_to_encode file_to_encode.comp”
