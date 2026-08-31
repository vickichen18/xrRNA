# xrRNA
Analysis of Xrn1-resistant RNA, classes: 1a, 1b, 2, 3 after alignment and array generation.

<img width="560" height="714" alt="image" src="https://github.com/user-attachments/assets/2759aa8c-cfc2-4ea5-b969-16f5c01c3337" />

Values near or at 0 bits demonstrate that corresponding positions are conserved across aligned sequences of their respective class. This  indicates that these positions account for the essential structures and/or functions of the molecule. The appearance of columns in the region between 1.5 to 2.0 bits demonstrate the presence of nonconserved regions, or regions that are not the same across alignments due to their lack of significance to change xrRNA's structure and/or function.

All classes of xRNA have entropies which vary widely across all positions, with the exception of the region approximately between positions 75-100 in the Class 1a xrRNA, possibly indicating high occupancy of indels ( "." for insertions and "-" for deletions) within the columns of the alignment (instead of bases AUCG). 


<img width="291" height="543" alt="image" src="https://github.com/user-attachments/assets/c02ddb4b-8a18-4dce-a4f2-9ce3a6ea52d8" />

The above kernel density estimations measure the confidence of the alignment of sequences within a given class against its constructed CM. 
The mean fit line within each plot represents the overall confidence for the alignment.
X-axis: Confidence score
Y-axis: How many of the sequences share a confidence score

Each kernel density plot is relatively narrow with means above 0.8. This means that the sequences and constructed CMs align relatively well, with high confidence. The narrow distribution and lack of multiple peaks indicate low variance and that sequences fit the corresponding model with equal confidence.

The Class 3 xrRNA is the most narrow, with a high peak at approximately 17, indicating high confidence (0.943) of sequence alignment against its CM. 

The Class 1b xrRNA is the most broad, with a peak at 5, indicating lower sequence alignment (0.811) confidence against its corresponding CM compared to the Class 3 xrRNA. 
