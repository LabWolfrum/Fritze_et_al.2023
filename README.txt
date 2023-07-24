As basic protocol Springer Nature Book "Intrinsically Disordered Proteins" ISBN 978-1-0716-0523-3 
Chapter 7 Nunez-Castilla & Siltberg-Liberles 2020 https://link.springer.com/protocol/10.1007/978-1-0716-0524-0_7 was used.

If you use this code, please cite Nunez-Castilla & Siltberg-Liberles 2020 and Fritze et al. 2023

Step by step protocol:

1. Original finding from NCBI (metazoa.xlsx)
	Blastp for USH1G/SANS was performed as described in Nunez-Castilla & Siltberg-Liberles 2020 and metazoa.xlsx was defined manually
2. blastp_search
	Code from folder
3. taxonomy_definition
	Code from folder
4. Iupred2A website was used https://iupred2a.elte.hu/ as input fasta_merged.txt from 2. was used
	Iupred2A results can be found in Iupred2A_output folder
5. Jalview was used as describe in Nunez-Castilla & Siltberg-Liberles 2020 and alignment was saved as Jalview_edited_length_wo_gap_delte_double.fasta
	See Iupred2A_to_gap folder
6. Iupred2.result.bin.fa was used for further analysis from 4.
7. Iupred2A gap included
	Code from folder
8. sort for vertebrate and mammals only
	Code from vertebrate_mammalia_sorted folder
10.analyzes with Excel and R-studio


This work is licensed under a Creative Commons Zero v1.0 Universal. 
https://github.com/LabWolfrum/Fritze_et_al.2023/blob/main/LICENSE

