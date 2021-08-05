#Passenger information given: 

Variable, Definition, Key
-------------------------
survival,	Survival,	0 = No, 1 = Yes
pclass,	Ticket class,	1 = 1st, 2 = 2nd, 3 = 3rd
sex,	Sex
Age,	Age in years
sibsp,	# of siblings / spouses aboard the Titanic
parch,	# of parents / children aboard the Titanic
ticket,	Ticket number
fare,	Passenger fare
cabin,	Cabin number
embarked,	Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton


Train.csv will contain the details of a subset of the passengers on board (891 to be exact) and importantly, will reveal whether they survived or not, 
also known as the “ground truth”.

The `test.csv` dataset contains similar information but does not disclose the “ground truth” for each passenger. It’s your job to predict these outcomes.

Results.csv contains the prediction results for test dataset (test.csv)

Titanic.ipynb is a Jupyter Notebook file and the code is in Python.
