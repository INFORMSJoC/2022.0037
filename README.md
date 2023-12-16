[![INFORMS Journal on Computing Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

# Cost-Effective Acquisition of First-Party Data for Business Analytics
This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

## Cite

To cite the contents of this repository, please cite both the paper and this repo, using their respective DOIs.

Below is the BibTex for citing this snapshot of the repository.
```
@article{LiuLi2023,
  author =        {Xiaoping Liu and Xiao-Bai Li},
  publisher =     {INFORMS Journal on Computing},
  title =         {Cost-Effective Acquisition of First-Party Data for Business Analytics},
  year =          {2023},
  doi =           {10.1287/ijoc.2022.0037.cd},
  url =           {https://github.com/INFORMSJoC/2022.0037},
} 
```

## Setup


A. Data files are included in the same folder along with the relevant code files.

B. Instructions for installing dependent software and packages:

B.1. Our programs are written in R and run in RStudio. RStudio must be installed in order to run our programs.

B.2. Also, install the following R packages before running our programs:

nloptr

dplyr

rpart

openxlsx2

reshape2

## Replicating

C. Instructions to run our programs and reproduce the results in the paper:

C.1. To reproduce the results in Figures 1 and 2 in the paper:

Open the folder named ‘music’ and run the R files in the following order:

music_DA_base01.R

music_DA_base02.R

music_DA_base03.R

music_DA_05.R (which outputs an Excel file with the results for Figure 1)

music_DA_10.R (which outputs an Excel file with the results for Figure 2)

C.2. To reproduce the results in Figures 3 and 4 in the paper:

Open the folder named ‘blackfriday’ and run the R files in the following order:

Friday_DA_base01.R

Friday_DA_base02.R

Friday_DA_base03.R

Friday_DA_05.R (which outputs an Excel file with the results for Figure 3)

Friday_DA_10.R (which outputs an Excel file with the results for Figure 4)

For more updated info, please check https://github.com/Xiaopingliu2023/ijoc02
