# Inverted Search Engine in C

## Overview

The Inverted Search Engine is a command-line application developed in C
that indexes words from multiple text files and creates an inverted index
using a hash table and linked lists.

The application allows users to create an index from input files and
search for words efficiently by retrieving the files in which the words
occur.

It also handles duplicate words and maintains occurrence information
for the indexed files.

## Features

- Create an inverted index from multiple text files
- Search for words in indexed files
- Display files containing a searched word
- Maintain word occurrence information
- Handle duplicate words
- Validate input files
- Use dynamic memory allocation
- Store indexed information using linked lists
- Perform file-based word processing

## Technologies Used

- C Programming
- Hash Tables
- Singly Linked Lists
- Pointers
- Dynamic Memory Allocation
- File Handling
- String Operations
- Structures

## Data Structures

### Hash Table

A hash table is used as the primary indexing structure. Words are
mapped to hash-table indices using a hash function.

### Linked Lists

Linked lists are used to maintain information associated with indexed
words and the files in which they occur.

The inverted index follows the concept:

    Word
      |
      +---- File 1
      |
      +---- File 2
      |
      +---- File 3

Instead of searching every file each time, the index allows the program
to retrieve the files associated with a particular word.

## Project Structure

    .
    ├── main.c
    ├── inverted.c
    ├── inverted.h
    ├── Operation.c
    ├── f1
    ├── f2
    └── f3

### Source Files

- `main.c` - Main program and user interaction
- `inverted.c` - Inverted index implementation
- `inverted.h` - Data structures and function declarations
- `Operation.c` - Operations related to index processing

### Sample Input Files

- `f1`
- `f2`
- `f3`

These files are used as sample input files for creating and testing
the inverted index.

## How It Works

The application reads words from the input text files and creates an
inverted index.

The general flow is:

    Input Files
        |
        v
    Read Words
        |
        v
    Calculate Hash Index
        |
        v
    Create / Update Index
        |
        v
    Linked List Management
        |
        v
    Inverted Index
        |
        v
    Search Word
        |
        v
    Display Matching Files

## Concepts Demonstrated

- Hash table implementation
- Singly linked lists
- Dynamic memory allocation
- Pointer manipulation
- File handling
- String processing
- Data structure implementation
- Memory management
- Modular C programming

## Learning Outcomes

- Gained practical understanding of hash-based indexing.
- Implemented singly linked lists for dynamic data management.
- Strengthened pointer and dynamic memory management skills.
- Learned to process and index data from multiple files.
- Implemented duplicate word handling and occurrence tracking.
- Improved debugging and problem-solving skills.

## Author

Divya Sai
