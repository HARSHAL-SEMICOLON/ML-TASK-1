# ML-TASK-1

House Price Prediction — Simple Beginner Project
This project is about predicting the prices of houses based on a few important details like how big the house is, how many bedrooms it has, and when it was built.

We’re using a basic machine learning model called Linear Regression. It’s one of the simplest ways to start learning how predictions work using data.

What You’ll Need
To run this project, you should have:
Python installed on your computer (version 3.7 or higher)
Some basic knowledge of how to run Python scripts

A few Python libraries:
You can install them with this command:
pip install pandas numpy scikit-learn

Files You’ll Work With
train.csv: This is your learning data. It has all the house features and their actual sale prices.
test.csv: This is new data with only features (no prices). We’ll predict the prices for these.
predict_house_prices.py: This is the Python code that does everything.
predictions.csv: After running the code, this file will contain the predicted prices for the test data.

How to Run It
Put the train.csv and test.csv files in the same folder as the Python script.
Open a terminal or command prompt in that folder.

Run the script using:
python predict_house_prices.py

When it finishes, check the folder for a file called predictions.csv. That’s where you’ll find your predicted prices.

What Data Is Used to Predict Prices?
The model looks at the following details about each house:
Size of the house (above ground area)
Number of bedrooms
Number of full bathrooms
Garage space (number of cars)
Size of the basement
Year the house was built
These features are picked because they usually affect how much a house sells for.

What Happens in the Background?
Don’t worry if you don’t know how everything works yet — here’s a simple summary:
Missing values in the data are filled in using the median value.
The features are scaled to make sure they're all on a similar range.
The sale prices are transformed using a logarithm to make the model learn better.
We split the training data to test how well the model is doing.
After training, we make predictions on the test data and save it.

Output Example
When you run the script, it’ll show something like:
Validation RMSE: 29000
Predictions saved to predictions.csv
This means your model is ready, and the predictions are saved.

Want to Try More?
Once you're comfortable with this, you can:
Add more features (like location or condition of the house)
Try more advanced models like Random Forest or XGBoost
Visualize your results with graphs

Why This Project?
If you’re just starting out with machine learning or data science, this is a great hands-on way to practice using real-world data and make meaningful predictions.


