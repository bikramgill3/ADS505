# Wells Fargo Elder Fraud Detection Modeling
---------------------------

This project is a part of the ADS-505 course in the Applied Data Science Program at the University of San Diego. This project utilizes a challenge structure produced by [MindSumo.com](https://www.mindsumo.com/) for the [Campus Analytics Challenge of 2021](https://www.mindsumo.com/contests/campus-analytics-challenge-2021) in partnership with Wells Fargo Bank of North America.  The soul purpose of this repo is to find a solution to the official challenge and submit it as part of a final project for Fall 2021's ADS-505 course at the Unviversity of Sand Diego.

-- Project Status: Active

## Contributers: 
* Cole Bailey
* Bikram Gill
* Christopher Richardson


# Installation
---------------------------
Data Exploration and Modeling was all done in [Jupyter Notebook](https://jupyter.org/).

### Dependencies:

This repo utilizes the following packages:

	* Matplotlib (>= 3.2.2)
	* Numpy (>= 1.19.5)
	* Pandas (>= 1.1.5)
	* Python (>= 3.7)
	* Scikit-Learn (>= 0.22.2)
	* Scikit-Plot (>= 0.3.7)
	* SciPy (>= 0.11.2)
	* Seaborn (>= 3.7)
	* StatsModels (>= 0.10.2)
	* XGBoost (>= 0.90)

To clone this repository onto your device, use the commands below:

	1. git init
	2. git clone https://github.com/bikramgill3/ADS505.git 



# Project Intro/Objective
---------------------------
Banks are required to report suspected vulnerable (elder and dependent adult) financial exploitation.

However, unless a customer reports fraud and files a claim, financial abuse can go undetected and repeated fraud via digital payments can continue without the banks’ knowledge. Without detection models, a large amount of fraud is left unreported by consumers and elder and vulnerable adult populations will be at greater risk of being targeted and losing savings to fraudulent payments.

It is currently not easy to detect fraud. Banks need better methods to help protect elder and 
vulnerable adults against fraud in the digital payments landscape. Predictive modeling may also be 
applied in some form to alert consumers and bankers in advance of a fraud attempt and potentially 
pre-empt certain transactions and monetary losses.

This project is an attempt to develop a model that can handle the class imbalance in this dataset (where cases of
fraud are the strong minority). F1 is the measure of choice that the bank would like to maximize, 
balancing the ability to detect fraud with the number of ‘alerts’ (predictions of Class 1) made. 


## Methods Utilized:
	* Decision Tree Classifier
	* Gaussian NB (Gaussian Naive bayes)
	* K Nearest Neighbors
	* KBins Discretization
	* Linear Discriminant Analysis
	* Logistic Regression
	* Random Forest Classifier
	* Standard Scaling
	* XGBoost Classifier (eXtreme Gradient Boosting)



# Acknowledgements
---------------------------
We would like to thank [MindSumo.com](https://www.mindsumo.com/) and [Wells Fargo North America](https://www.wellsfargo.com/) for providing students with a real world challenge in which Data Science may be utilized for a better tomorrow.
<br><br>
## Important Links
Challenge website: [Mind Sumo](https://www.mindsumo.com/contests/campus-analytics-challenge-2021)

Note: Dataset included in this repository is "proprietary to Wells Fargo and it may not used for any other purpose than to provide a Solution in this Challenge" (Wells Fargo Bank, N.A., 2021).

# For a better tomorrow!







