# IRON-KAGGLE-PROJECT
The objective is to predict the revenue of shops.
Each row of our data contains the following information:

shop_ID : Shop's unique identifier.
day_of_the_week : Encoded from 0 to 6.
date : day, month and year of the data point.
number of customers : Quantity of customers that showed up that day.
open : Binary variable equal to 0 if shop closed that day and 1 if shop open.
promotion : Binary variable equal to 0 if shop had no promotions that day and 1 if it did.
state_holiday : Encoded 0, a, b, c indicating if there was a state holiday at all (0 if not), and otherwise, the number indicates which state holiday it was.
school_holiday : Binary variable equal to 1 if there was a school holiday that day and 0 if not.
Your submission  should consist of an output file with just the index and sales prediction for the row, as well as a pickled version of your model, a requirements.txt file and any feature engineering steps you may have used (preferably pickled as well).

Deliverables:

output file with columns: index, prediction;
model in a pickle file
feature engineering in a pickle file (if you can't, submit your feature engineering processing in a jupyter notebook)
requirements.txt

We must be able to run your model and generate predictions in our computers, so we strongly advise you to try to emulate in a clean environment what we would do and see if you are delivering all necessary artifacts.

The scoring metric will be R2.
