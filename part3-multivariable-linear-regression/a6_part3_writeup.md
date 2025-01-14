# Part 3 - Multivariable Linear Regression Writeup

After completing `a6_part3.py` answer the following questions

## Questions to answer

1. What is the R Squared coefficient for your model? What does that mean about the model in relation to your data?
0.86, a decently high r squared value. this means that my model is a bit inaccurate compared to data

2. Is your model accurate? Why or why not?
its a ok, while you can use it it would be wise to take the information with grain of salt

3. What does the model predict a 10-year-old car with 89000 miles is worth? What about a car that is 20 years old with 150000 miles?
9191.94539359 for 10 year and 2100.5206231 for 20 year

4. You may notice that some of your predicted results are negative. This is occurring when the value of age and the mileage of the car are very high. Why do you think this is happening?
the modle was never told to stop at 0 so the line never stops, and as the line has a negitive slope, when the line goes below 0 it starts becoming negitive.