The ipython notebook holds my solutions to Use Case 1 for the entry level position in the product team at Gramener. 

The solution was written in python, using Intel's MKL and python distribution channels. 

The libraries used are primarily pandas for dataframe manipulation and seaborn to draw plots, with a smattering of numpy and scikit-learn 

In order to answer the three questions, I used correlation matrices to determine the important/impactful features, then used bar and distplots in order to compare performance between student categories. 

Cleaning the data was a problem - my solution uses about 30% of the total given dataset, which is far from ideal. However I wanted to minimize the chances of tainting the target variables by mean replacement or any other form of statistical interpolation of missing data as that can severely reduce the accuracy of the analysis/model in my experience. 

Also the notebook is written in python 3, though not many of the features of python 3 were required to be used. 