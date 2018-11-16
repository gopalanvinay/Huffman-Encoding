# Huffman-encoding
HW7 Huffman encoding
Vinay Gopalan

The Encoder uses BitIO's functionality to read characters from files and uses Huffman to determine how the
characters should be encoded. It then accesses a .comp file and writes into the file.
Decode reverses the process and writes into a .comp.palintext file. 

files:	name				raw size	compressed size		match
	bee_movie			55,339		32,307			yes
	id_ascii			11,791		5,505			yes
	ascii_arts			11,077		4,510			yes
	huffman_homework_description	9,645		5,926			yes
	bible_new			3,880,246	2,222,159		yes	

