# SocialSentimentAnalyzer
Social Sentiment Analyzer with Comment Classification

## Features

- Logistic regression model for comment classification.
- User-friendly web interface for inputting comments and viewing predictions.
- Kaggle dataset integration for training and testing.

## Getting Started

1. Install dependencies
2. Run the Flask web application (`app.py`) to interact with the sentiment analysis tool.
3. Explore the Jupyter notebook (`comment classification project.ipynb`) for details on the model building process.

For a more detailed guide, refer to the sections below
Project structure
├── data/
│   └── comments.xlsx      # Place your Kaggle dataset here
│
├── model/
│   └── comment classification project.ipynb  # Jupyter notebook with the model building using logistic regression
│
├── web_app/
│   ├── templates/
│   │   ├── comment.html       # HTML form for inputting comments
│   │   └── answer.html        # HTML page displaying the predicted comment status
│   │
│   ├── app.py                 # Flask application to serve the web app
│  
│
├── README.md                  # Project documentation

