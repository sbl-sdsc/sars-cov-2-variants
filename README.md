# SARS-CoV-2 Variant Metadata in Parquet format

This repository contains the SARS-CoV-2 variant metadata in the Parquet compressed format in the data directory:

* data/variants.parquet

The [download_variants.ipynb notebook](notebooks/download_variants.ipynb) downloads SARS-CoV-2 variant metadata from [China National Center for Bioinformation](https://bigd.big.ac.cn/ncov/release_genome), standardizes the column names and data, and saves the results as a .parquet file.

The [read_variants.ipynb notebook](notebooks/read_variants.ipynb) shows an example how to read selected columns from the .parquet file into a Pandas dataframe.


