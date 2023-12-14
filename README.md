# Google Restaurants Data Mining Project

This project attempts to predict an arbitrary customer’s star rating of a restaurant from the provided Google Restaurants Dataset, specifically from the filtered subset dataset. Following an exploratory analysis of the data, we decided that the best approach to predicting the star ratings would be through text mining utilizing linear regression. Our methodology involved multiple experiments on the training set to determine the optimal number of words to include in our feature vector. To enhance the predictive capabilities of our model, we conducted operations on the predicted values of our valid set, including clipping to minimum and maximum values of the star ratings, as well as rounding, thereby refining our predictions against the baseline. Notably, our investigation revealed that the leftward skewness and non-Gaussian distribution of the star ratings graph resulted in the most negatively weighted words possessing greater magnitudes than their positively weighted counterparts in the linear regression model's theta coefficients.

Dataset found here: [Google Restaurants Dataset](https://drive.google.com/drive/folders/1lMyaUW8VgXEojpjiMMrt-VC5uPeZ3al0)[^1]

[^1]: Personalized Showcases: Generating Multi-Modal Explanations for Recommendations
An Yan, Zhankui He, Jiacheng Li, Tianyang Zhang, Julian Mcauley
arXiv:2207.00422, 2022
