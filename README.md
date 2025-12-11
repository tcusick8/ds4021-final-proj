# ds4021-final-proj

# Project Synopsis

This project aims to find which factord are best to predict the location of a crime in Chicago. The data set used is from the City of Chicago data portal on public safety. Our group queried the data to include input from November 2020 to November 2025. The models we used to find a relationship between crime and location were a penalized ridge regression, support vector machine, random forest, and neural network. Factors included to predict a relationship were primary type, arrest, domestic, date, description, and year. Our best model ended up being the penailzed ridge regression, resulting in a MSE of 0.005527. However, throughout every model, we could not find a strong relationship between the crime variables and location, suggesting there isn't an accurate way to predict the location of a crime based off the limited varibales we had. 

## Software and Platform Selection

The python version used for the Neural Network, Random Forest, and SVM models is 3.13.1. The python version used for the penalized linear model and final test notebook was 3.12.6. Each model is kept in its own jupyter notebook with the title matching the model configuration. Packages used include pandas, numpy, ast, time, matplotlib, scikit-learn (linear_model, multioutput, preprocessing, pipeline, compose, metrics, model_selection, svm, ), and pytorch. All members of the group operated on a Mac operating system. 

## Documentation Map
Our repo is mapped out as follows:

NOTEBOOKS:
- EDA.ipynb
- Neural_Network.ipynb
- RF-final.ipynb
- NVM.ipynb

  
OUTPUT:
- EDA Visualizations
- NN Folds
- RandomForest Output

data:
- Test Sets (this is a link to a Google Drive because the files were too large to store directly in Github)

README.md
