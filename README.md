# huffman-coding
Huffman Coding Implementation [Python]

## What is Huffman Coding?
Huffman coding is a lossless data compression algorithm. The idea is to assign variable-length codes to input characters, lengths of the assigned codes are based on the frequencies of corresponding characters.

This implemenation uses Heaps and DFS

# How To?
## Run
1. Run huffman.py with inpute file
```
python huffman.py supporting_files/huffman_starter.txt 
```

### Output
- ./supporting_files/huffman_starter.txt_encoded
- ./supporting_files/huffman_starter.txt._encoded_decoded

### Verify
If the code is correct the oupt in the decoded file should match the input file. You can use any diff program to check this.

