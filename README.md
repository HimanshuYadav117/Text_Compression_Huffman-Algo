# Text_Compression_Huffman-Algo
The project showcases how huffman algorithm can be used for Text file compression based off on the number of unique characters and frequency of each character.
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters. The most frequent character gets the smallest code and the least frequent character gets the largest code.

Hence the more the frequency of characters (The number of repeating characters) More will be the Compression Ratio.

Commands For Execution In Linux Environment--

-LINUX COMMANDS-

For Generating the Compiled Encode file -- gcc Encoding.cpp -o Encode -lstdc++
 
For Generating the Compiled Decode file -- gcc Decoding.cpp -o Decode -lstdc++  

For Encoding - ./Encode DEMO.txt	   //    ./Compiled_encoding_file _file_to_encode

For Decoding - ./Decode DEMO.txt.sha.txt  //    ./Compiled_Decoding_file _file_to_decode
