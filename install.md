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

# Installing Homebrew on a M1 Mac
* Create a duplicate of the terminal Application (Cmd + d on the terminal)
* Rename the duplicate (Terminal (x86))
* Right click the duplicate and click "Run with Rosetta"
* Then proceed to paste: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
* Homebrew should install correctly
* use "arch -arm64 brew" (install) to do anything

RUN
`
pip install -U scikit-learn
pip install numpy
pip install scipy
`
