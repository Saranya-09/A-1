# Q-3
#This Python script is designed to analyze a genetic sequence and count the occurrences of all possible 3-letter combinations (also known as triplets or codons) found in the sequence. The script reads the genetic sequence from a .fasta file (ignoring the header), performs the triplet analysis, and then prints out the results in alphabetical order.
The script follows three main steps:

Extract the Genetic Sequence: It reads a genetic sequence from a given file, ignoring any header lines (such as those in FASTA format). The sequence is stored as a single string in uppercase.
Analyze Triplet Occurrences: It scans the genetic sequence for every possible 3-letter combination (triplet) and counts how many times each triplet occurs in the sequence.
Print the Analysis Results: The results (triplet and their counts) are printed in alphabetical order for easy viewing.
Files
sequence.fasta: This is the file where your genetic sequence should be stored. The first line is typically a header (which is ignored), and the following lines contain the sequence data.
Usage
To use the script, follow these simple steps:

Place your genetic sequence file in the .fasta format in the specified path (e.g., C:\sequence.fasta).
Run the Python script. It will read the sequence, perform the triplet analysis, and display the results.
Functions in the Script
extract_genetic_sequence(file_path):

Takes the file path of the genetic sequence as input.
Reads the file and returns the full genetic sequence as a single string.
It skips the first line of the file, which is assumed to be a header.
analyze_triplet_occurrences(genetic_string):

Takes the full genetic sequence string as input.
Counts the occurrences of all 3-letter combinations (triplets) and returns a dictionary where keys are triplets and values are their respective counts.
print_triplet_analysis(triplet_data):

Takes the dictionary of triplet counts as input.
Prints each triplet and its count in alphabetical order.
