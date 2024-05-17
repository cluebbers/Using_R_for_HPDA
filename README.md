# Using R for High-Performance Data Analytics

## Overview

This repository contains the seminar report and associated materials for the course "Newest Trends in High-Performance Data Analytics" at Georg-August-Universität Göttingen.
The report investigates the use of R in high-performance data analytics (HPDA), focusing on memory management, GPU computing, parallel processing, and benchmarking.

## Repository Structure

```
├── README.md
├── 2024-03-25_R_HPDA_Luebbers.pdf      # Detailed insights into leveraging R for high-performance data analytics
├── NTHPDA.Rmd                          # R notebook containing example code and benchmarks
```
## Report Highlights

- **Memory Management**: Techniques to optimize R's memory usage for handling large datasets.
- **GPU Computing**: Utilizing GPU for accelerated computations with R packages.
- **Parallel Processing**: Methods to perform parallel computations to speed up data processing tasks.
- **Benchmarking**: Evaluating the performance of various R functions and comparing them with Python.
- **Leveraging C++**: Enhancing R's performance by integrating C++ code.
- **Computational Biology**: Using R for high-performance data analysis in genomics and bioinformatics.
- **Comparative Analysis**: Evaluating R's performance against Python for various data processing tasks.

## Code

To run the example scripts, you need to have R installed on your system along with the necessary packages.
You can install the required packages using the following commands:


1. **Install the required packages**

```R
install.packages(c("forcats", "readr", "dplyr", "tidyr", "ggplot2", "tibble", "devtools"))
```

2. **Download the data**

The data can be found here: https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Datasets/DVS/natality/Nat2018us.zip

3. **Knit the R Markdown file**

Open the `NTHPDA.Rmd` file in RStudio and click the "Knit" button to generate the HTML report. 
Alternatively, you can use the following command in your R console:

```R
rmarkdown::render("NTHPDA.Rmd")
```

## Future Work

Making gpuR work :)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or feedback, please contact Christopher L. Lübbers at c.luebbers@stud.uni-goettingen.de.
