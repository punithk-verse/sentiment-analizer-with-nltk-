# sentiment-analizer-with-nltk-
basic
Sentiment Analyzer Chatbot using NLTK
📌 Overview
This is a simple Python-based chatbot that analyzes the sentiment of user input using NLTK's SentimentIntensityAnalyzer.
It classifies text as Positive, Negative, or Neutral based on the sentiment score.

✅ Features
Interactive chatbot in the terminal.
Real-time sentiment analysis for any sentence.
Easy to use and beginner-friendly.

🚀 How to Run

Clone the repository:
Shellgit clone https://github.com/your-username/sentiment-analyzer-chatbot.gitcd sentiment-analyzer-chatbotShow more lines


Install dependencies:
Shellpip install nltkShow more lines


Download NLTK resources:
Pythonimport nltknltk.download('vader_lexicon')Show more lines


Run the script:
Shellpython sentiment_chatbot.pyShow more lines



🖥️ Example Output
Chatbot Sentiment Analyzer (type 'exit' to quit)
Enter a sentence: I love Python programming!
Scores: {'neg': 0.0, 'neu': 0.341, 'pos': 0.659, 'compound': 0.6696}
Positive statement detected 😊
----------------------------------------
Enter a sentence: This is terrible.
Scores: {'neg': 0.611, 'neu': 0.389, 'pos': 0.0, 'compound': -0.6249}
Negative statement detected 😞
----------------------------------------


✅ Requirements

Python 3.x
NLTK library


📜 License
This project is licensed under the MIT License – feel free to use and modify.
