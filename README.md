# peptideMapping data pipeline
This is a data pipeline repo to generate fasta files and open format mzML files, that are followed by spectra matching. 

# generating fasta files 
Fasta files are generated based on two distinct modules, namely, to generate each individula fasta file (fastaGen), and then to combine fasta files (fastaConcat). 
fastaGen module is scripted based on overwriting a fasta template (attached file). The user inputs are protein ID, protein description, protein sequence, and fasta file name. 
fastaConcat module combines multiple fasta files. The user inputs are the number of fasta files to be combined, their names, and the output fasta file name. Each individual fasta file is uploaded one at a time. 

# spectra matching

# quantitative analysis
