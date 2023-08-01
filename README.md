# AlignTaxa
# Language: Python
# Input: TXT
# Output: CSV
# Tested with: PluMA 1.1, Python 3.6
# Dependency: scipy==1.4.1

PluMA plugin that takes a time-series dataset of metabolites and performs
warping.

The plugin takes as input a tab-delimited file of keyword-value pairs:

dataFilename: CSV input file
useSplines: Whether or not to use spline interpolation
referenceSampleID: Unique identifier of reference sample

Output file is a CSV file of rankings
