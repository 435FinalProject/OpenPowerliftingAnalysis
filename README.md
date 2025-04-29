# OpenPowerliftingAnalysis
Instructions for Replicating Our Project: 
Make sure you have Python3 installed. Clone repository, `cd` into the directory, then run `pip3 install project_requirements`. 
To Run the Entire Pipeline:

1. Use `jupyter notebook` and open the notebook files. 
2. Go to [OpenPowerlifitng Data Service]([https://link-url-here.org](https://openpowerlifting.gitlab.io/opl-csv/bulk-csv.html)) and download the `openpowerlifting-latest.zip` file. Unzip the file and place the .csv file in the `data/` directory.
3. Run the Preprocess.ipynb Notebook to preprocess the data and generate the male and female datasets.
4. Run the Age_Weight_Models.ipynb notebook to train and test multiple ML models (Random Forest, Gradient Boosted Decision Tree, ElasticNet, Ridge Regression, Lasso Regression) on our preprocessed male and female datasets, and see the results.
5. Run [Lionel's models here] in notebook
6. Have fun experimenting. 

Enjoy!
