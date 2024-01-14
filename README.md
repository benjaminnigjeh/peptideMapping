# peptideMapping data pipeline
This is a data pipeline repo to generate fasta files and open format mzML files, that are followed by spectra matching. The spectra matching output, fasta files, and mzML files are imported to SKYLINE. The SKYLINE report is exported as a CSV file, and will be used for quantitative purposes.
![UML class](https://github.com/benjaminnigjeh/peptideMapping/assets/108296284/cd98a56a-ef31-4079-b93b-26a6e85e25ba)


# generating fasta files 
Fasta files are generated based on two distinct modules, namely, to generate each individula fasta file (fastaGen), and then to combine fasta files (fastaConcat). 
fastaGen module is scripted based on overwriting a fasta template (attached file). The user inputs are protein ID, protein description, protein sequence, and fasta file name. 
fastaConcat module combines multiple fasta files. The user inputs are the number of fasta files to be combined, their names, and the output fasta file name. Each individual fasta file is uploaded one at a time. 

# spectra matching

# quantitative analysis
