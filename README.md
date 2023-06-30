# 2coat-or-not-2coat

### Should I take a coat with me when I leave the house today?

We check the weather each morning and make this decision without really thinking - but how can we train a machine learning model to make this decision for us? 

#### Model inputs
The model is baded on the following three numeric inputs:

- Temperature (Celcius)
- Precipitation chance (percent)
- Wind speed (mph)

#### Notebook structure
1. The notebook first creates a training dataset by randomly generating weather conditions, summing the numerical values and setting wear_coat as True or False based on the overall weather score
2. The notebook then creates a linear regression model based on the training dataset
3. Finally, the notebook asks for user input for the day's weather conditions, and then calls the model to predict whether a coat is required and return a human-readable output: "It is TRUE/FALSE that you should wear a coat today"

#### Possibilities
There are many different ways this code could be improved upon or adapted to fit different use cases. It aims to be a simple introduction to machine learning via a linear regression model - but improvements could be made by using:
- different machine learning models,
- real training data,
- API calls to open source datasets,
- a UI,
- more refined training parameters e.g. scaling the score to weight rain chance as more important than wind speed,
- more training parameters e.g. activity (what the user will spend the day doing)
- more prediction capabilities e.g. should I wear a rain coat and/or gloves and/or a jumper today?
