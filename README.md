## AB-Testing-Gym-Membership

#### Evaluate Hypothesis that fitness test intimidates some prospective members of the Gym.

### Description

#### A/B Testing

Randomly assign visitors to the following two groups:
* **Group A** : Gym visitors who are asked to take a fitness test with a personal trainer.
* **Group B** : Gym visitors who are asked to proceed directly to fill in the application, skips the fitness test.

#### Hypothesis

* **Null Hypothesis (H0)** : There will **no difference between the visitors** in Group A that purchase membership and the visitors in Group B that purchase membership.
* **Alternate Hypothesis (H1)** : There will be **more visitors in Group B** that will purchase membership **than visitors in Group A** that will purchase membership.
* The significance threshold we will set as the benchmark to either accept or fail to reject the null hypothesis will be: 𝛼 = 0.05

#### Intersting Learnings:  

- [x] How to determine if statistical significance is important or not ?
- [x] How to build Hypothesis ?
- [x] How to choose a hypothesis test for a given problem ?

### Install Setup

This project requires **Python 2.7** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org)
- [scipy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.


### Code

Template code is provided in the notebook `ab_test_gym_membership.ipynb` 
[Jupyter Notebook](https://github.com/YRohitha/AB-Testing-Gym-Membership/tree/main/app/ab_test_gym_membership.ipynb) file.


### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
jupyter notebook ab_test_gym_membership.ipynb
```
or
```bash
ipython notebook ab_test_gym_membership.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.


### Data

There are multiple files in the dataset used in this project will be included as `fitness_tests.csv`, `purchases.csv`, `visits.csv`, `applications.csv` 
This dataset is sourced from [codeacademy](https://www.codecademy.com/learn) and contains the following attributes:

**Description**

This data set contains all the records of users for a virtual Gym.

**Features**

`fitness_tests.csv` : Details about the person who took a fitness test
- `first_name` : First name  
- `last_name` : Last name 
- `email` : e-mail 
- `gender` : Gender 
- `fitness_test_date` : The date when the person took a fitness test

`purchases.csv` : Details about the Customer who purchased the membership, sent in their 1 month's payment
- `first_name` 
- `last_name` 
- `email` 
- `gender` 
- `purchase_date` : Invoice date and time. The day when a transaction was generated.

`visits.csv` : Details about users who visited the Gym. Note: Not all visits are generated during the A/B Testing period.
- `first_name` 
- `last_name` 
- `email` 
- `gender` 
- `visit_date` : The day when the user visited the Gym. 

`applications.csv` : Details about users who filled out an application for the gym.
- `first_name` 
- `last_name`
- `email`
- `gender` 
- `application_date` : The day when the user filled out an application for the gym.

### Conclusion
Gym visitors that completed a fitness test (Group A), were more likely to make a purchase than those visitors that did not complete a fitness test (Group B).
