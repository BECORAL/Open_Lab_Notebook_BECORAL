#BRAKER3: Protein prediction from genome

[Galaxy] (https://usegalaxy.eu) hosts multiple bioinformatics tools that are run from the GUI rather than the command line in Terminal. You can register for a free online account with 250 GB of output storage.

BRAKER3 uses RNA-Seq and/or predicted protein databases to guide protein prediction from a genome in .fna or .fasta format. RNA-Seq data are submitted as BAM files (very large) while predicted protein files are submitted as .fa or .fasta files obtained from NCBI or Uniprot (preferred) which are much smaller.

These instructions predict and then combine exons from your genome of interest into likely genes based on a guiding high-quality genome, converts those genes into protein sequences, and then assess the quality of those protein predictions. Instructions draw heavily from [Galaxy’s BRAKER3 tutorial] (https://training.galaxyproject.org/training-material/topics/genome-annotation/tutorials/braker3/tutorial.html) with modifications.
