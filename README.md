# Supreme_Court_Decisions
For our MIS 5470: Practical Computing for Data Analytics Course.
<b></b>
We performed data wrangling, manipulation, feature engineering, exploratory data analysis, data visualization, and predictive modelling to gain an understanding to generate predictions using a [Supreme Court Cases Dataset](https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction/data) in order to predict the outcome of major Supreme Court decisions (**first party winner**: the first party being the appellant). 

View our process and analysis on [YouTube](https://www.youtube.com/watch?v=qdOOZli1tJo)!
## Instructions (If you'd like to run the analysis yourself)
1. Run [Notebook.ipynb](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/Notebook.ipynb).
This Jupyter notebook contains all of the sequential code for running our analysis to be followed! *Be wary, the grid search method for finding the best parameters for some modelling techniques can be temporally and computationally extensive.*
3.  Enjoy! :)  

## Results
![Results](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/images/sc_results.png)

The baseline model of assuming no lower court decision reversals is able to predict the first party winner with 64.0% accuracy.

The NLP only Counts-BOW Random Forest outperformed all other tests (marginally) with an accuracy of **66.8%**, being closely followed by the 66.7% logisitic regression missing NLP features and the 66.7% accuracy with TFIDF BOW logistic regression. Several models were able to slighly **outperform** (up to 2.8%).

## Files
* [Notebook](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/Notebook.ipynb): Contains all analysis for predicting Supreme Court Judgements.
* [images](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/tree/main/images): Contains all image files for project.
* [MIS5470final.html](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/MIS5470final.html) Html file of Notebook.
* [Supreme_Court_Judgments.pdf](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/blob/main/Supreme_Court_Judgments.pdf) Visually appealing PowerPoint of Notebook process.
* [csvs](https://github.com/brandonowens24/MIS5470_Supreme_Court_Decisions/tree/main/csvs): Contains all data used in the Notebook file.
    * [Supreme Court Cases Dataset](https://www.kaggle.com/datasets/deepcontractor/supreme-court-judgment-prediction/data)
    * [Presidential Years in Office Dataset](https://github.com/awhstin/Dataset-List/blob/master/presidents.csv)
    * [Supreme Court Justices Data](https://supreme.justia.com/justices/)

## Authors
* Hailey Naugle (M.S. Applied Statistics Graduate Student at Oakland University)
* Brandon Owens (M.S. Applied Statistics Graduate Student at Oakland University)
