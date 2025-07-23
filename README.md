# DoomScrollDetector

## Doomscrolling Detector 🕵️‍♂️
This project aims to detect when a user is doomscrolling based on simulated phone and social media usage data.

The detector uses a Logistic Regression model trained on simulated user data. I wanted to use real data but unfortunately doom scrolling has only been a recent thing so there is not enough data or studies on it yet.

The model identifies doomscrolling based on a combination of factors, including late-night usage, negative content sentiment, long session lengths, and a high number of scrolls.
The Doomscrolling Detector is a Jupyter Notebook project that uses simulated phone data to identify when someone is doomscrolling. It sets up the necessary tools, creates fake user data (including what they looked at and its mood), and gets this data ready for a simple prediction model. The model is then trained and checked to see how well it works. Finally, the notebook shows how it can predict doomscrolling for a new session and give a helpful warning.

The model's accuracy is revealed by the classification report and confusion matrix. Based on the simulated data, the model shows high precision when predicting a user is not doomscrolling. However, it has a moderate recall for doomscrolling, correctly identifying 50% of those instances. Overall, the model achieves high accuracy, indicating good performance on this simulated dataset.

If the data ever come out for doomscrolling I would love to re-do this project using real data.
