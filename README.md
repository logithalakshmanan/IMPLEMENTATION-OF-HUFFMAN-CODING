# Huffman Coding Algorithm

## Aim

To implement the Huffman Coding algorithm in Python for generating variable-length binary codes based on the frequency of characters.

## Description

Huffman Coding is a lossless data compression technique. It assigns shorter binary codes to frequently occurring characters and longer codes to less frequent characters.

## Algorithm

1. Get the input string.
2. Calculate the frequency of each character.
3. Create nodes for each character and its frequency.
4. Sort the nodes based on frequency.
5. Select the two nodes with the smallest frequencies.
6. Combine them to create a new node.
7. Repeat until a single Huffman tree is formed.
8. Traverse the tree to generate Huffman codes.
9. Display each character and its Huffman code.

## Input

The input string used in the program is:

`huffman coding`

## Output

The program displays each character along with its corresponding Huffman code.

Example format:

```text
Character | Huffman Code
-------------------------
    h     |    ...
    u     |    ...
    f     |    ...
```

## Requirements

* Python 3.x
* No external libraries are required.

## Conclusion

The Huffman Coding algorithm was successfully implemented in Python. The program generates unique binary codes for the characters based on their frequencies.
