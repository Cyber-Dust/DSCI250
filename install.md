## Installing miniconda

Download miniconda from https://docs.conda.io/en/latest/miniconda.html

After successful installation, Run-- MAC: shasum -a 256 filename

Run-- conda install jupyter into terminal (iTerm2)

Run-- jupyter notebook

!!BOOM, You are ready for Data Science!!

Run-- 
conda install matplotlib

conda install pandas

conda install seaborn

how to read a csv file:

Run--
import pandas as pd

company = pd.read_csv("fortune500.CSV")

print(company)



HOW TO CALCULATE SUMMARY STATISTICS
https://pandas.pydata.org/pandas-docs/stable/getting_started/intro_tutorials/06_calculate_statistics.html

Run-- .describe()
