# NBAmatchpredictor
Webscraping from official NBA website and applying machine learning algorithms to predict winner between NBA teams

For this project, I chose to use both a Ridge Classification for the initial run-throughs.
After achieving sub-optimal results, decided to use a more advanced and compelx model: Random Forrest Classifiers. 
I was able to achieve much higher accuracy at the expense of computation.

-------------
Here are the steps I took for this project:

- The first step is to scrape data from the official website to have relevant information to feed into the models

- The second step is to remove any unnecessary data that may be influencing the model to predict wrongly (e.g. date, season, and etc.)

- The third step is choosing a viable algorithm that will predict correctly consistently on validation data

- The step in between 3 and 3 is to keep testing different models until satisfiable success if found

- The forth  step is to change different hyperparameters to increase validation accuracy

- The last step is running and reporting the accuracy of the chosen model

-------------

In the future, I plan to apply this to the NCAA tournament brackets to receive a good estimator for the next NCAA Basketball Tournament.
