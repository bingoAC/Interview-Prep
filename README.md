# Data Analyst 

### Job Requirements
- Acquire, review and research new data
- Automate data retrieval and produce derived datasets
- Work with traders to design and implement new applications for data
- Enhance data analysis platform

- Python, KDB/q, Unix, SQL. Familiarity with Jupyter Notebook is a plus
- Team player, good communication skills, self-starter, detail oriented
- Bachelor's degree majoring in Statistics / Computer Science / Math / Engineering or related fields
- Advanced quantitative and data science skills in Python. Familiarity with equity trading and finance a plus
- 2+ uears experience required Qualifications

## Review Directions

### Data Science Knowledge Review

1. **Supervised Learning vs Unsupervised Learning**

    ![image](https://user-images.githubusercontent.com/26676751/53687910-076b8e00-3d09-11e9-8516-d14f8c692287.png)

    - **Supervised Learning** is where you have input variables (x) and an output variable (Y) and you use an algorithm to learn the mapping function from the input to the output.
    Y = f(X). 
    The goal is to approximate the mapping function so well that when you have new input data (x) that you can predict the output variables (Y) for that data.
    
        - Common Algorithm:
	
	1. **Logistic regression**: is the appropriate regression analysis to conduct when the dependent variable is dichotomous (binary). Predictive analysis. Logistic regression is used to describe data and to explain the relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent variables.
		- Type of questions that a binary logistic regression can examine:
			- How does the probability of getting lung cancer (yes vs. no) change for every additional pound a person is overweight and for every pack of cigarettes smoked per day?
			- Do body weight, calorie intake, fat intake, and age have an influence on the probability of having a heart attack (yes vs. no)?
		    
	2. **Naive Bayes**: a conditional probability model: given a problem instance to be classified, represented by a vector x = (x1, …, xn) representing some n features (independent variables), it assigns to this instance probabilities for each of K possible outcomes or classes. 
		![image](https://user-images.githubusercontent.com/26676751/53700513-2b8aa600-3dc1-11e9-9a4b-11e0c4747724.png)
                ![image](https://user-images.githubusercontent.com/26676751/53700516-40673980-3dc1-11e9-89a5-39654961093e.png)
                ![image](https://user-images.githubusercontent.com/26676751/53700568-d13e1500-3dc1-11e9-887b-400bb3676d24.png)
                ![image](https://user-images.githubusercontent.com/26676751/53700612-1d895500-3dc2-11e9-80eb-ae15e3178dd2.png)
		* Pros
			* East & Fast to predict a class of test dataset
			* Performs better compared to other models assuming independence
			* Performs well in case of categorical input variables compared to numerical variables
		* Cons
			* Zero Frequency when not observable (add 1)
		            * Relies on independence assumption and will perform badly if this assumption is not met
                    
	3. **Support Vector Machine**: is a discriminative classifier formally defined by a separating hyperplane. Given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples. In two dimentional space this hyperplane is a line dividing a plane in two parts where in each class lay in either side.
	    	* Pros
			* Performs similarly to logistic regression when linear separation
			* Performs well with non-linear boundary depending on the kernel used
			* Handle high dimensional data well
		* Cons
			* Susceptible to overfitting/training issues depending on kernel
			
	4. **Random Forest**: Random forest builds multiple decision trees and merges them together to get a more accurate and stable prediction.
	
		* Pros
			* It can be used for both regression and classification tasks and that it’s easy to view the relative importance it assigns to the input features.
			* important when dealing with mulitple features which may be correlated
			* reduced variance (relative to regular trees)
		* Cons
			* Not as easy to visually interpret
			* A large number of trees can make the algorithm to slow and ineffective for real-time predictions
	
	
    - **Unsupervised Learning** is where you only have input data (X) and no corresponding output variables.
    The goal for unsupervised learning is to model the underlying structure or distribution in the data in order to learn more about the data.
    
	1. **K-means Clustering**: identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.
		* pros
			* Simple to implement and flexible
			* Efficient, tight clusters and easy to interpret
		* cons
			* No-optimal set of clusters
			* Lacks consistenct
			* Only handle numerical data
			* Specify k-values
			
	2. **Principle Component Analysis**: 
			
2. **Overfitting & Underfitting**: 
	- In overfitting, a statistical model describes random error or noise instead of the underlying relationship. Overfitting occurs when a model is excessively complex, such as having too many parameters relative to the number of observations. 
	- Underfitting occurs when a statistical model or machine learning algorithm cannot capture the underlying trend of the data. Underfitting would occur, for example, when fitting a linear model to non-linear data.
	
3. **Data Cleaning**:
	- Cleaning data from multiple sources helps to transform it into a format that data analysts or data scientists can work with.
	- helps to increase the accuracy of the model in machine learning
	- It is a cumbersome process because as the number of data sources increases, the time taken to clean the data increases exponentially due to the number of sources and the volume of data generated by these sources.
	- It is a cumbersome process because as the number of data sources increases, the time taken to clean the data increases exponentially due to the number of sources and the volume of data generated by these sources.

4. **Eigenvectors & Eigenvalues**
	- Eigenvectors are the directions along which a particular linear transformation acts by flipping, compressing or stretching.
	- Eigenvalue is the strength of the transformation in the direction of eigenvector or the factor by which the compression occurs.

5. **Linear Regression** is a statistical technique where the score of a variable Y is predicted from the score of a second variable X. X is referred to as the predictor variable and Y as the criterion variable.

6. **Steps for an analytics project**
	- Understand the Business problem
	- Explore the data and become familiar with it
	- Prepare the data for modeling by detecting outliers, treating missing values, transforming variables, etc.
	- After data preparation, start running the model, analyze the result and tweak the approach. This is an iterative step until the best possible outcome is achieved
	- Validate the model using a new data set
	- Start implementing the model and track the result to analyze the performance of the model over the period of time
	
7. **Central Limit Theorem**: In some situations, when independent random variables are added, their properly normalized sum tends toward a normal distribution even if the original variables themselves are not normally distributed.
	![image](https://user-images.githubusercontent.com/26676751/53706774-eb93e500-3df9-11e9-829b-bdfbc6401d29.png)
	![image](https://user-images.githubusercontent.com/26676751/53706539-e2564880-3df8-11e9-8881-1378b013cce1.png)

8. **Law of Large Number**: As the number of identically distributed, randomly generated variables increases, their sample mean (average) approaches their theoretical mean.


### Future Trading Challenge

1. Concept:

	- Candlestick chart: 
	![image](https://user-images.githubusercontent.com/26676751/53826939-cf05c300-3f47-11e9-90e5-b0f811940319.png)
	
	- Moving Average Buy & Sell:
	![image](https://user-images.githubusercontent.com/26676751/53827938-44729300-3f4a-11e9-9733-7ff36cf7b068.png)
		- Set-up: Fast MA set (5 day & 20 day), Slow MA set (36 day & 90 day)
		- Simple Move Average (SMA): 
			![image](https://user-images.githubusercontent.com/26676751/53831624-3d9c4e00-3f53-11e9-8cc4-c93ed3ed2890.png)
		- Exponential Moving Average (EMA): 
			![image](https://user-images.githubusercontent.com/26676751/53831697-67ee0b80-3f53-11e9-8a94-da6eeb3f5335.png)
		- Moving Average Convergence Divergence (MACD): a trend-following momentum indicator that shows the relationship between two moving averages of a security’s price. 
			- MACD is calculated by subtracting the 26-period EMA from the 12-period EMA
			- MACD triggers technical signals when it crosses above (to buy) or below (to sell) its signal line.
			- The speed of crossovers is also taken as a signal of a market being overbought or oversold.
			- MACD helps investors understand whether bullish or bearish movement in the price is strengthening or weakening.
		
	- Open Range Breakout: (By Toby Crabel, 1990 "Day Trading with Short Term Price Patterns")
		![image](https://user-images.githubusercontent.com/26676751/53831842-c74c1b80-3f53-11e9-84b9-a157ee519471.png)
		![image](https://user-images.githubusercontent.com/26676751/53831933-fd899b00-3f53-11e9-9514-dc61b0964fff.png)
	
	

### Jupyter Notebook, luigi task and tools Review


### Equity Trading - Delta One product Knowledge Review


### Brainteasers, 
