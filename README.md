# red_wine_quality
I made a study about the quality of wines.

First, given a wine, my goal was to classify it according to its 'quality'. The 'quality' variable can assume the following values: 3, 4, 5, 6, 7, 8.

After that, I created a new attribute, called 'binary', to model a binary classification: "good" wines and "not good" wines. My criterion was: If the quality is major or equal than 7, it's a "good" wine. Otherwise, it's a "not good" wine.

After training different models, I got the following models as being the best ones:

- Random Forest to the classification between 3, 4, 5, 6, 7 and 8. After testing, I obtained a best performance with these features: 'volatile acidity', 'chlorides', 'free sulfur dioxide', 'total sulfur, dioxide', 'density', 'sulphates' and 'alcohol';

- Logistic Regression to the classification between "good" and "not good". I obtained a best performance with these features: 'volatile acidity', 'chlorides', 'residual sugar', 'pH', 'free sulfur dioxide', 'density', 'total sulfur dioxide', 'sulphates' and 'alcohol'.