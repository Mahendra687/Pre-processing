Pre-processing in Genome Analysis

 **In Quality Control**, the purpose of performing the **Read Quality Control** to understand your raw data, make informed decisions on how to handle it and maximise your chances of getting a good quality assembly.
  
  **Some of the important information of QC is:** 
1. Read types: Will be important in setting maximum k-mer size value for assembly
2. Number of reads: Gives you an idea of coverage
3. GC content: High GC organisms don’t tend to assemble well and may have an uneven read coverage distribution.
4. Presence of highly recurring k-mers: may point to contamination of reads with barcodes, adapter sequences etc.
5. Presence of large numbers of N’s in reads: May point to poor quality sequencing run. You need to trim these reads to remove N’s.
  
  **Genome indexing** is the pre-processing technique that allows the aligner to compress the size of the genome and also make searching the genome faster for a query sequence within the genome by decreasing time/space and increasing the efficiency of the aligner. 
  
**Genome annotation** is the process of attaching biological information to sequences. It consists of three main steps: identifying portions of the genome that do not code for proteins, identifying elements on the genome, a process called gene prediction, and attaching biological information to these elements.

1. Structural Annotation: Sequence Features and Gene Prediction
2. Functional Annotation: Similarity Searches (BLAST) and Identification of Gene Clusters

