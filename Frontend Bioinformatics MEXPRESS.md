MEXPRESS: A software that aids in visualizing\
expression, DNA methylation and clinical TCGA data\
Authors (@slack): Minella Akudinobi (@FrauMinella), Hiba-tul-noor(@Hibistic),\
Hibaq Yusuf (@Hibaq)\
A growing number of clinical and genomic cancer data has been made publicly\
available in recent years thanks to large-scale collaborative programs like The\
Cancer Genome Atlas (TCGA) and University of California, Santa Cruz (UCSC) Cancer\
genome browser. These datasets will remain useless as long as they are hard to\
access and understand.\
MEXPRESS is an intuitive web tool designed after the principles of graphical\
excellence, for the fast querying and visualization of the clinical, expression and\
methylation data of these available datasets and the relationship between these\
datasets on a single gene level. It ensures that the complex TCGA data would be\
presented in a clear, precise and efficient way to the user.\
Implementation and application of MEXPRESS\
MEXPRESS features creating a plot which results in an image that can downloaded\
in a PNG or SVG file format. To create this plot, a user has to enter a gene name,\
select an available cancer type and click the plot button.\
The blue line plot illustrates the methylation for each probe location, the yellow line\
plot displays the RNA-seq-derived expression data and the grey bar plots represent\
the values of clinical parameters. The numbers on the far right indicate the\
significance of the relation between each row of data and the selected expression\
value. The significance mentioned above is calculated using statistical analysis\
functions in MEXPRESS which include the Pearson correlation and non-parametric\
Wilcoxon’s rank sum test. The former is used to compare two types of data that has\
more than 2 level i.e., expression and methylation data while the latter is used to\
calculate the variable difference between two groups.\
Researchers studying prostate cancer have used MEXPRESS to explore the\
expression of the gene GSTP1 while also investigating how its methylation status\
correlates with patient outcomes. The tool was also used to analyze the gene MLPH,\
a breast cancer marker, revealing how its methylation levels differ between various\
breast cancer subtypes and how these differences relate to its expression.\
Conclusion\
The availability of TCGA data is a tremendous asset, its utility is maximized by\
platforms like MEXPRESS, which bridge the gap between data complexity and user\
accessibility. These insights can help uncover new therapeutic targets and improve\
our understanding of the molecular mechanisms driving different cancers.\
Reference

Koch, A. et al. (2015) ‘MEXPRESS: Visualizing expression, DNA methylation and \
clinical TCGA data’, BMC Genomics, 16(1). doi:10.1186/s12864-015-1847-z.

linkedIn link:
https://www.linkedin.com/posts/hiba-noor-a40054285_mexpress-hackbio-internship-activity-7238263996993200128-IhaA?utm_source=share&utm_medium=member_desktop
