# HuffmanEncodingChallenge
Coding challenge to make the fastest huffman encoding

## Purpose
The purpose of this challenge is to do some good mental exercise and stretch parts of our skills that we may not usually use.

## What the program will do

In the Source folder is a very large document. You may test against this document to see your solution work. The test document is different and (hopefully) will not be available outside of the test. Your goal is the following:
- Compress the document using the [Huffman Encoding algorithm](https://www.kosbie.net/cmu/fall-15/15-112/notes/notes-data-compression.html), and write that file out to disk. Do NOT overwrite the original document. Name it something different.
- Decompress your compressed document using a decompression algorithm to reverse your compression. Do NOT overwrite the original, your decompressed document will be compared to it.
- Your program must conform to the following:
  - The program will be started with 2 parameters:
    - "compress" or "decompress" to dictate the direction of the algorithm
    - The name of the file to operate on.


## Rules
1. You may NOT call a pre-build zip/encoding/built-in library or algorithm to perform the work for you and submit that. you must do the work yourself.
2. You MAY use pre-built data structures if you want, or you can build them yourself if you think you have an optimization.
3. Your entry point must be runnable from a shell script that calls your 'main' method. See the [What the program will do](#What the program will do) section to see the contract.
4. Submissions will be peer reviewed to ensure entries are not skirting the intentions of this contest.

## How to make a submission
1. Make a branch off of this repo and make a new folder at the root of the project with your name/username/something everyone will know is yours.
2. Copy whatever you want from the Source folder to your own, but do not modify anything in the Source folder.
3. use whatever IDE to write your program.
4. Make a PR to get others to veryfy validity.
5. profit?

Winner gets bragging rights.
