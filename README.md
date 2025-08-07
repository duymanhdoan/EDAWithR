# EDA with R 

### Install mini anaconda 
https://www.anaconda.com/docs/getting-started/miniconda/install#macos-linux-installation 


### Setup environment 
```
cd ./EDAWithR
conda env create -f environment.yml -n my-env 
conda activate my-env 

```
### Run code with Jupyter Notebook 

```
open file: eda-with-r.ipynb 
and type:  jupyter notebook . 
```

### Notice: 
- Change your excel file path in main function: 
    ```
    file_excel_path <- "~/src/r-projects/ketqua2.xlsx"
    ```
- The output file will display in 
    ``` 
    './output/' folder. 
    ``` 