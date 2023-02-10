# Assembler Comparison
## Bioinformatics Capstone 2023, Cal Poly SLO
Report by Ava Jakusovszky, Rachel Koenigsberg, and Priyanka Chandar

Repository built for clients to have access to the source code for working directories for Platanus and SPAdes Assemblers. MaSuRCA was never able to be ran, but the source code can be found [here.](https://github.com/alekseyzimin/masurca)

### Data
Data was sourced from:
Anthrax: https://www.ebi.ac.uk/ena/browser/view/SRX798106
S. Aureus: https://www.ebi.ac.uk/ena/browser/view/SRR747869
E. Coli https://figshare.com/articles/dataset/E_coli_sequencing_data_for_blogpost/9758411
Aspergillus Fumigatus: https://trace.ncbi.nlm.nih.gov/Traces/?view=run_browser&acc=ERR9791667&display=download

Due to the size of files, we recommend gathering the data directly on the server using 
```
  curl <link> --output <name of file with appropriate file type>
  #if applicable
  gunzip <.gz file>
```

### Assembler Access
The files included in each assemblers' respective directories are the environments in which each assembler ran or did not run. Some resources, like QUAST, were not necessary for running.

Checkout QUAST [here](https://quast.sourceforge.net/docs/manual.html#sec1)

### View the Comparison Report
! link to be inserted !
