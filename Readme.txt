we have taken the main data file from the following link
      https://www.kaggle.com/iliassekkaf/computerparts?select=All_GPUs.csv
      
The first part was data analysis which is done in file name:
      DataAnalysis.ipynb

After analysing all the data we were having 34  columns in total out of
which 28 were having some null values. So for the data wranngling the file
was divided into two parts containing 14 rows each. Data wrangling resulted
in following changes:
      Data wrangling PART 1.ipynb:
          In this file first 17 rows were appilied with data wrangling techniques
          and a new csv was formed named as:
                Data_wrangling_PART_1.csv:
                      This file had further data wrangling in a file named
                      as:
                          DataWrangling_part2.ipynb:
                              It resulted in formation of a final csv file 
                              which is:
                                  DataWrangling_part2.csv


After all above we were having a final file DataWrangling_part2.csv on which all
other task were performed:
                            
      Data Visulaization using Matplotlib.ipynb
      Binning.ipynb
      Correlation.ipynb
      Linear Regression.ipynb

