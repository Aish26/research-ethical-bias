# ⚙️ Ethical Bias in Machine Learning 
### 🍀 Motivation

#### AI bias in COMPAS

- Correctional Offender
Management Profiling for
Alternative Sanctions
- US court systems
- Likelihood of defendant
being rearrested
- Predicted **twice** as many
**false positives** for black
offenders than others


#### Gender bias in lending

- AI systems for loan
approvals and amounts
- European banks
- Black and Hispanics 80%
more likely to be rejected
- Women approved amounts
14,000 euros lower on
average


#### Bias in hiring

- Resume ranking </br>
- Amazon’s recruiting engine
- Trained on historical data
- Penalized the word
“ women’s ”
- Little significance to skills
not found on men’s
resumes


### 🌵 Sources of Bias

- Gender
- Race
- Age
- EthnicityReligion


### 📚 Problem Statement
Matching: Can the users be matched on data other than demographic? 
Spending behavior? 
Social Network? 

Prediction: Can we predict user behavior without using demographic data?
 How well? 
 
### 🔖 Data Sources and Features

- Face ++
- Venmo

#### 📊Demographic Features
Identifies the user demographic details

- Race
- Gender
- Age

#### 📺 Social Network Features
Identifies the user social network behavior

- Friends
- Friends of Friends
- Clustering coefficient

#### 💰 Transactional Features
Identifies the user spending behaviour

- Recency
- Frequency
- Activity

### 🔄 Matching Methodology 
- Data processing by creating social network and transaction features
- Propensity score using logistic regression
- Identify Matched Pairs using K-Nearest Neighbour
- Deviance Comparison between demographic and behavioral features
<img width="778" alt="Screenshot 2023-06-25 at 7 31 15 PM" src="https://github.com/Aish26/research-ethical-bias/assets/27972590/29ffa601-a89b-4108-9923-2f396a67066c">



### 🔁 Prediction Methodology 
- Data processing by creating social network and transaction features
- Train and test split
- Regression analysis
- Mean squared error comparison between demographic and behavioral features
<img width="775" alt="Screenshot 2023-06-25 at 7 31 23 PM" src="https://github.com/Aish26/research-ethical-bias/assets/27972590/832bf3f0-0ead-477d-a768-b44f735056f1">



