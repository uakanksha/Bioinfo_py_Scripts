# Bioinfo_py_Scripts
## Python Scripts for Bioinformatics
### gc_percent.py
This script take FASTA file as input and return the GC content
```
$ python gc_percent.py <FASTA_File>
```
### extract_accession_no.py
This script take MULTI-FASTA file as input and write all the Accession Number(s) in a new file (accession_no.txt)
```
$ python extract_accession_no.py <Multi_FASTA_File>
```
### extract_fasta_headers.py
This script take (Multi)Fasta file as input and write the Sequence Header(s) in a new file (fasta_headers.txt)
```
$ python extract_fasta_headers.py <Multi_FASTA_File>
```
### k-mer_constructor.py
This script take Fasta file as input and produce all the K-mers of length specified by the user
```
$ python k-mer_constructor.py <FASTA_File>
```
### random_seq_generator.py
This script take sequence-type and sequence-length as input and produce random-nucleotide-sequence in FASTA format
```
$ python random_seq_generator.py
```
### extract_fasta_records.py
This script extracts Fasta-records from Multi-Fasta file whose Accession-No(s) are in Accession-Ids file
```
$ python extract_fasta_records.py <Multi_FASTA_File> <Accession_IDs_File>
```
### fasta_record_finder.py
This script extract Fasta-record from Multi-Fasta file whose Accession-No is inputted by the user and write the record in a new file (NC_XXXXXX.fasta)
```
$ python fasta_record_finder.py <Multi_FASTA_File>
````
### fasta_concatenator.py
This script merge all the files with (.fasta) extension and create a new file (multi_fasta)
```
$ python fasta_concatenator.py
```
### multi_fasta_deconcatenator.py
This script split multi fasta file into individual fasta file(s)
```
$ python multi_fasta_deconcatenator.py <Multi_FASTA_File>
```
### file_comparison.py
This script compare two files and return the elements present in one file but not in other
```
$ python file_comparison.py -f1 <File_1> -f2 <File_2>
```
### ftp_download.py
This script download all the files whose ftp addresses are listed in ftpfilepaths file
```
$ python ftp_download.py <ftpfilepaths>
```
### dna_fasta_visualization.py
This script take DNA fasta file as input and return Accession number, Organism/Origin, Base count, Sequence length, GC content, AT content and whether the sequence is GC rich or AT rich
```
$ python dna_fasta_visualization.py -n <FASTA_File>
```
