# **RESCUE**
Resolving \
Species-level \
Classification \
Using \
Emu

Updated pipeline and Methods for 16S-ITS-23S rRNA Nanopore Sequencing with Custom Barcodes.

Last update: January 20, 2023

This repo serves as a functional pipeline to perform bacterial classification and abundance analysis using Nanopore sequencing technologies. The pipeline was created specifically to use custom barcoded RRN amplicons to sequence using Nanopore. The primers listed here create a 4,500bp fragment containing the entire 16S rRNA, the intergenic spacer region, and most of the 23s rRNA. Theoretically, any primers you choose can work for this pipeline as long as contraints in the programs are changed. For further information about the pipeline and the results of a validation study, please visit (and cite) the following publications from the Triplett Lab:

```
RESCUE: a Validated Nanopore Pipeline to Classify Bacteria Through Long-Read, 16S-ITS-23S rRNA Sequencing (2022)
```

## **Installation**
This package can be installed using conda 
```
'Phosphate' -- 'Linker' -- '16-mer barcode' -- 'primer' 
```
