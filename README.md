# TopHashtagsWithFibonacciHeaps

## Project Description 
Implemented a system to find the n most popular hashtags appeared on social media such as Facebook or Twitter. For the scope of this 
project, hashtags will be given from an input file. Basic idea for the implementation is to use a max priority structure to find out the 
most popular hashtags.

## Data Structures
The following structures are used for the implementation.
1. Max Fibonacci heap: use to keep track of the frequencies of hashtags.
2. Hash table: Key for the hash table is hashtag and value is pointer to the corresponding node in the
Fibonacci heap.

## Execution
The makefile document creates a executable file named hashtagcounter. Program requires the input file name as an argument. <br />
Following is an example execution of the program that read from a input file named file_name.<br /> <br />
java  hashtagcounter file_name
