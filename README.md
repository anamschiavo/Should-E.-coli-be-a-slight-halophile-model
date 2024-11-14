# Should-E.-coli-be-a-slight-halophile-model
R script and raw data of the article "Should E. coli K-12 substrain MG1655 be a slight halophile model?" submitted to Microbiology Open

## Raw data
The files **"MS1655_1.tsv"**, **"MS1655_2.tsv"** e **"MS1655_3.tsv"** are the CFU counting data of the growth curves of *Escherichia coli* K-12 MG1655 in different NaCl concentrations. Each file is a biological replicate.

## e_coli_ufc.R
This file is the R script to process the raw data and fit the Baranyi model to the growth curves. It also generates all the graphs in the article (main text and appendix).
### Input
All the MS1655_x.tsv files.
### Output
Graphs and a table with all the growth rates given by the Baranyi model in a file called **"mumax_tab.tsv"**.
