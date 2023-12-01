---
permalink: /teaching/
title: "Teaching"
author_profile: true
redirect_from: 
#  - /lp/
  - /teaching.html
---
# Here you can find links to Miura lab github tutorials for sequencing analysis

* Here is the link to [Lecture 2](https://uconnmiura.github.io/comp_camp/lectures/lecture_2.html), the intro to short read RNA-seq

* Here is the link to [How to setup and use conda](https://uconnmiura.github.io/comp_camp/lectures/setup_1.html)

* Here is a python script bedmaker4.py (for tutorial use)

```
#!/usr/bin/env python
### conda env is pandas_1

import pandas as pd

def read_and_clean_data(csv_filename):
    """
    Reads a CSV file into a DataFrame and performs initial cleaning.
    """
    genes = pd.read_csv(csv_filename)

    # Selecting specific columns and rearranging their order
    # determine this by inspecting the csv columns. column number starts with 0
    genes_cleaned = genes.iloc[:, [1, 2, 3, 0, 5]]

    # Inserting a placeholder column "Stars" with default value "0" at column 5
    genes_cleaned.insert(loc=4, column="Stars", value="0")
    
    return genes_cleaned

def main():
    # Assuming you want to use the same filename for both reading and exporting
    csv_filename = "Saito_Exc_Nova2.csv"
    bed_filename = csv_filename[:-4] + ".bed"

  # Print input filename to stdout
    print("The input file is", csv_filename)

    # Read and clean the data
    genes_cleaned = read_and_clean_data(csv_filename)

  # Print output filename to stdout
    print("The output file is", bed_filename)

    # Export the cleaned data to BED format
    genes_cleaned.to_csv(bed_filename, sep='\t', encoding='utf-8', index=False, header=False)

if __name__ == "__main__":
    main()

```