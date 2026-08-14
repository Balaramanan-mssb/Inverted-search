# Inverted-search
A file-based search engine that builds an inverted index using hash tables and linked lists to efficiently search for words across multiple text files.

📌 Project Overview

Inverted Search is a file-based search engine implemented in C using Hash Tables and Linked Lists. The project creates an inverted index that maps each word to the files in which it occurs, along with its occurrence count. This allows users to efficiently search for a word across multiple text files without scanning every file repeatedly.

🎯 Objectives

->Build an inverted index for multiple text files.

->Store words and their corresponding file information.

->Search for words efficiently using hashing.

->Track the number of occurrences of each word in each file.

->Demonstrate practical usage of Hash Tables, Linked Lists, Structures, and File Handling.

🛠️ Technologies Used

Programming Language: C

Data Structures: Hash Table, Linked List

Concepts: File Handling, Pointers, Structures, Dynamic Memory Allocation

Compiler: GCC

Platform: Linux / Ubuntu

⚙️ Features

1. Create Database

Reads words from the input files and creates an inverted index.

2. Display Database

Displays the complete inverted index, including:

->Index value

->Word

->Number of files containing the word

->File names

->Word occurrence count in each file

3. Search Database

Searches for a given word and displays the files in which the word occurs and its frequency.

4. Update Database

Allows additional files to be added to the existing database.

5. Save Database

Stores the generated database in a file for future use.

🧠 Data Structure Concept

The project uses a hash table as the primary data structure.

Each hash-table index contains a linked list of words. Each word maintains information about the files in which it appears.

Hash Table
   |
   +--- Index 0
   |
   +--- Index 1
   |      |
   |      +--- Word
   |             |
   |             +--- File 1 → Count
   |             +--- File 2 → Count
   |
   +--- Index 2
   |
   +--- ...

🔄 Working Flow

Input Text Files

       ↓
       
Read Words

       ↓
       
Calculate Hash Index

       ↓
       
Store Word in Hash Table

       ↓
       
Store File Information

       ↓
       
Store Occurrence Count

       ↓
       
Create Inverted Index

       ↓
       
Search / Display / Update / Save

📂 Project Structure

Inverted_Search/
│

├──main.c

├── create.c

├── display.c

├── search.c

├── update.c

├── save.c

├── inverted.h

├── types.h

└── README.md

🖥️ Sample Input

Enter the choice:
1. Create Database
2. Display Database
3. Search Database
4. Update Database
5. Save Database
6. Exit

📚 Concepts Learned

Through this project, I gained practical experience in:

->Hashing

->Hash tables

->Singly linked lists

->Structures and pointers

->Dynamic memory allocation

->File handling in C

->String manipulation

->Modular programming

->Searching and indexing

->Command-line applications


 


