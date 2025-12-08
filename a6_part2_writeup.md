# Assignment 6 Part 2 - Writeup

---

## Question 1: Feature Importance

Based on your house price model, rank the four features from most important to least important. Explain how you determined this ranking.

**YOUR ANSWER:**
1. Square Feet 
2. Bedrooms
3. Bathrooms
4. Age

**Explanation:**

Square feet had by far the strongest correlation. Bedrooms and bathrooms had similar correlation with it being moderate with a visible trend. The one with the weakest correlation and leats visible trend was age so I ranked it least important.


---

## Question 2: Interpreting Coefficients

Choose TWO features from your model and explain what their coefficients mean in plain English. For example: "Each additional bedroom increases the price by $___"

**Feature 1:**
Each additional bedroom increases the price by $6,648.97. 

**Feature 2:**
Each additional bathroom increases the price by $3,858.90.

---

## Question 3: Model Performance

What was your model's R² score? What does this tell you about how well your model predicts house prices? Is there room for improvement?

**YOUR ANSWER:**


0.9936 is my R² score. This means that the model explains 99.36% of price variation. This means that the models predictions are about 99% accurate. There is about .64% room for improvement. 

---

## Question 4: Adding Features

If you could add TWO more features to improve your house price predictions, what would they be and why?

**Feature 1:**
Structural damage

**Why it would help:**

This could help because it can make a more accurate prediction. Structural damage can greatly impact the price of a house and is someting that should be included.

**Feature 2:**

live in ready

**Why it would help:**

The circumstances of the house also play a part because if a house is live in ready it costs more than one thats a fixer upper.
---

## Question 5: Model Trust

Would you trust this model to predict the price of a house with 6 bedrooms, 4 bathrooms, 3000 sq ft, and 5 years old? Why or why not? (Hint: Think about the range of your training data)

**YOUR ANSWER:**

I would use it as a very rough estimate and would not use it for an important or accurate estimate. It may be able to get a close estimate but the range for beedrooms,bathrooms, and sq ft are not fit for my models practice date so it may not generate the best equation because it does not have an example to go off of. So I might trust it for a roug estimate but it wont be that accurate
