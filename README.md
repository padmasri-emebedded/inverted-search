Project Overview
This project implements an inverted index system that maps content (words/numbers) to their locations across multiple documents. Using hash-based data structures, it enables fast and efficient full-text search operations, similar to the fundamental technology behind search engines.

Features
Multi-Document Indexing: Create indexes across multiple text files
Fast Search: Quick retrieval of words and their occurrences
Frequency Analysis: Track word frequency within documents
Database Operations: Save and load index data to/from files
Advanced Search: Boolean search operators (AND, OR, NOT)
Scalable Structure: Hash table implementation for efficiency

Technologies Used

C Programming Language
Data Structures:
Hash Tables
Linked Lists
File I/O Operations
String Processing
Dynamic Memory Management

How It Works

Parsing: Documents are parsed and words are extracted
Indexing: Each word is mapped to its document locations using a hash table
Storage: The inverted index is stored in memory as a hash table with linked lists
Searching: User queries are processed to find matching documents
Persistence: Indexes can be saved to and loaded from disk

Key Learnings

Implementing complex data structures like inverted indexes
Designing efficient hash functions and collision resolution strategies
Managing data persistence with specific format requirements
Organizing and retrieving large volumes of text efficiently
Database integrity maintenance techniques
