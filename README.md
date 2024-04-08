# MIS5470_Supreme_Court_Decisions
We performed data wrangling, manipulation, feature engineering, exploratory data analysis, data visualization, and predictive modelling to gain an understanding to generate predictions using a [Supreme Court Cases Dataset](https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction/data) in order to predict the outcome of major Supreme Court decisions. 

## Instructions (If you'd like to run the analysis yourself)
There is a file labelled [Notebook.ipynb](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/Notebook.ipynb). This Jupyter notebook contains all of the sequential code for running our analysis to be followed! 

Be wary, the grid search method for finding the best parameters for some modelling techniques can be temporally and computationally extensive.

## Results
![Results](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/images/sc_results.png)

The NLP only Counts-BOW Random Forest outperformed all other tests (marginally) with an accuracy of **66.8%**, being closely followed by the 66.7% logisitic regression missing NLP features and the 66.7% accuracy with TFIDF BOW logistic regression. Several models were able to slighly **outperform** (up to 2.8%) the Baseline Model of assuming no lower court reversal in decision (of any part) that sat at 64.0% accuracy. 

## Files
* [Notebook](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/Notebook.ipynb): Contains all analysis for predicting Supreme Court Judgements.
* [images](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/tree/main/images): Contains all image files for project.
* [csvs](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/tree/main/csvs): Contains all data used in the Notebook file.
    * [Supreme Court Cases Dataset](https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction/data)
    * [Presidential Years in Office Dataset](https://github.com/awhstin/Dataset-List/blob/master/presidents.csv)
    * [Supreme Court Justices Data](https://supreme.justia.com/justices/)

## Authors
* Hailey Naugle (M.S. Applied Statistics Graduate Student at Oakland University)
* Brandon Owens (M.S. Applied Statistics Graduate Student at Oakland University)
