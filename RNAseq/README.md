The RNAseq workflow is as follows:
  1. bbduk_PE.q
  2. fastqcreport.q
  3. multiqc.sbatch
  4. hisat2_PE.q
  5. merge_bams.sbatch
  6. bamTobw.q
  7. featureCounts.q
  8. deseq2.R

