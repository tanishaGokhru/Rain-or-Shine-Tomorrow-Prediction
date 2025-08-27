🌦️ Rain or Shine Tomorrow Prediction
Problem Statement

The Rain in Australia dataset contains 10 years (2007–2017) of daily weather observations from numerous Australian stations. As a data scientist at the Bureau of Meteorology, the task is to build an automated system that predicts whether it will rain tomorrow at a given location using today’s weather data.

Approach

Leveraged the Rain in Australia dataset (145K+ records), splitting data into training, validation, and test sets by year.

Handled missing values using mean imputations and normalized numerical features with Min–Max scaling (0–1) for balanced impact.

Trained and evaluated a Logistic Regression model, achieving ~85% accuracy, with detailed performance analysis using a confusion matrix.

Tech Stack

Python • Pandas • NumPy • Scikit-learn • Matplotlib • Seaborn
