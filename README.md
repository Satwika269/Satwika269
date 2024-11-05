📚 Similarity Checking from Books

🎯 Overview

An elegant text analysis project that explores the fascinating relationships between 64 literary works. Using sophisticated comparison algorithms, this project uncovers hidden patterns and similarities in classic literature.

Code Data Given:

A simple (but crude) way to measures similarity is given as following:
Identify top 100 frequent (normalize) occurring words in a text file. Consider only
numeric character and alphabet character (by converting both small and capital
alphabets to capital form) of the text file. Normalize the word count of a file by
dividing total number of words in the file.

◦ remove commonly occurring six specific words “a”, “and”, “an” , “of” “in” and
“the” from the file at the time of counting frequent word, total number of word
and the normalize frequency.

Similarity index of two files can be calculated as sum of normalize value of all the
frequent words occurred in both the files.

Create a 64x64 size similarity matrix.

Report top ten similar pairs of text books using the similarity matrix. You need to
exclude the self similarity.

Data Set:

https://drive.google.com/file/d/1jcm_-q3IzrDD7lCg0yMlH_GJbg8wudir/view?usp=sharing

✨ Key Features

Identifies the 100 most influential words across the literary corpus

Generates a comprehensive 64x64 similarity matrix

Reveals the top 10 most closely related book pairs

Processes and analyzes raw text with precision

Implements robust comparison algorithms

📊 Results Highlight

Our analysis revealed some fascinating connections between books. Here are some notable findings:

Gerard's Herbal volumes show remarkable similarity (91% match between Vol. 3 and Vol. 4)

Memoirs of Laetitia Pilkington demonstrates strong narrative consistency across volumes

Foxes Book of Martyrs maintains thematic coherence throughout different parts

🛠️ Technical Implementation

Core Components

Custom Book class for efficient text representation

Advanced text preprocessing pipeline

Sophisticated similarity calculation algorithms

Comprehensive word frequency analysis

Technology Stack

Language: C++

Data Format: Raw text files

Analysis Method: Statistical text comparison

📈 Performance

The program efficiently processes 64 books and performs:

Word frequency analysis across entire corpus

2,016 unique book-to-book comparisons

Similarity ranking and sorting

🚀 Getting Started

Clone the repository

Ensure all book text files are in the designated directory

Compile the C++ source files

Run the executable

Find results in the output directory

📝 Output Files

The program generates several output files:

common_words.txt: Top 100 most frequent words

similarity_matrix.txt: Complete comparison matrix

similar_books.txt: Top 10 most similar book pairs

🔍 Future Scope

Natural Language Processing integration

Interactive visualization dashboard

Semantic analysis capabilities

Genre classification features

Multi-language support


🤝 Special thanks to:

The professors for their guidance

The open-source community for inspiration

Project collaborators for their valuable input

Submission from - IITGCS_24061110 ( TAMMISETTI SESHA SATWIKA )
