### Introduction
The way to run this is to use the enviroment.yml to create a conda environment.
You can either run main or all the numbered cells individually its the same code with minor changes to account for using multiple notebooks.
The structure is as follows:
```
├── README.md
├── Environment.yml           # Dependencies for Conda
├── main.ipynb
├── 1_Data_Preparation.ipynb
├── 2_KPIs.ipynb
├── 3_Site_Classification.ipynb
├── 4_Clustering.ipynb
├── 5_Regression.ipynb
├── intermediate_data         # to make multiple notebooks work
└── Data_Share/               # Standardized folder name (no spaces)
    ├── Charging_Sessions.csv
    └── Weather_Burbank_Airport.csv
```

The main file are structured like this the single files are analog
1. Data Setup and Cleaning: Initializing the environment and preprocessing the raw CSV files.
2. KPIs: Calculation and visualization of the three primary Key Performance Indicators.
3. Site Classification: Determining and distinguishing between Private and Public sites.
4. Clustering: Adding further parameters needed for clustering and determining a good number of clusters.
5. Regression: Training the regression model and adding further parameters to aid with the training
