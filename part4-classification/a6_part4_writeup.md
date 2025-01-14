# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
before: .8 to .9 
after: .77 to .88

the scaler just makes sure all the data is weighted the same.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
before varies from .8 to .9 because of train test split variation. this is decenty accurate though resultes might vary if your accutialy using it to predict things.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
it had an accuracy of 0.84.it even had places where it had  nearly the same inverse of the predicted output as a general pattern. 

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
no


