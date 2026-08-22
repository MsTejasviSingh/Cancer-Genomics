## Quality Control Results

A MultiQC report summarizing sequencing quality across all RNA-seq samples is available here:

[multiqc_report.html](https://github.com/user-attachments/files/31329661/multiqc_report.html)

The report was generated from FastQC analysis of all FASTQ files and provides an overview of sequencing quality metrics, GC content, duplication levels, and adapter contamination.

## MultiQC Quality Control Summary

MultiQC was used to aggregate FastQC reports from all 24 sequencing files.

### Key observations

- All samples showed similar GC content (~47–48%), indicating consistency across the dataset.
- Sequencing depth ranged from approximately 0.6 to 1.3 million reads per sample.
- Per-sequence GC content displayed a near-normal distribution centered around 50% GC.
- No major outlier samples were observed.
- Several samples generated warnings for GC content distribution; however, no samples failed quality control metrics.

Overall, the sequencing data appears to be of acceptable quality and suitable for downstream RNA-seq analysis.
