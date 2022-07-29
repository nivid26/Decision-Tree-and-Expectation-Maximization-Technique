General Requirements:
•To install following packages and library use ‘pip install’ following with name of the library in the Jupyter Notebook. It is necessary to install all libraries to code run and this code can be used in any python code compiler such as Google Colab and VS code.
•Numpy
•Impyute
•Math
•Collection
•Chefboost
•Openpyxl

•Replace the following for different files folder, starting with place number according to folder number in first 2 lines in place of “1” in the Last Cell of code file
•Then, replace the value of count to current cell number of “Table-NRMS.xlsx” file for that data set number.
•Finally, pass folder number as first argument of the function “filename”. Before running this cell in Jupyter make sure to run all cell above it and it has no error.
•Set path as per your computer location of complete dataset(Last Cell and For Code 2 and Code for 12,13,14 files also in second last cell), incomplete data set(Last Second Cell), Table-NRMS.xlsx(Last Second Column) and where we have to save imputed data(Last second cell).

Code1.ipynb used for where all files have few instances without NaN values, total columns less than 80.
Code2.ipynb used for where file are without complete instances means all code contains one or more NaN.
Code with PCA(Data 7).ipynb used if total column are greater than 80 such Data 7. Also, it is same code contain if loop if 		         file doest not have any column without NaN value then it replace randomly picked column from complete                       			   dataset.
Code for 12,13,14.ipynb used for data file with larger number of rows, used it but do not know wheteher it is correct or not.
