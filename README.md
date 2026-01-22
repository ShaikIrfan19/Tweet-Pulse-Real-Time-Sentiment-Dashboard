# Tweet Pulse: Real-Time Sentiment Monitoring and Visualization Dashboard

## Project Overview
Tweet Pulse is a real-time sentiment monitoring and visualization dashboard designed to analyze public opinion from live Twitter data. The system integrates Natural Language Processing (NLP), Machine Learning, and data visualization techniques to extract actionable insights from social media streams.

## Objectives
- Classify tweets into positive, negative, or neutral sentiments
- Monitor live Twitter streams using keywords or hashtags
- Identify trending topics using topic modeling
- Correlate sentiment trends with extracted topics
- Visualize insights through an interactive dashboard

## System Modules
### 1.Sentiment Classification
- Uses ML/DL models such as Logistic Regression, Naïve Bayes, and BERT
- Processes cleaned tweet text to predict sentiment labels

### 2.Live Twitter Stream Monitoring
- Fetches tweets in real time using Twitter Streaming API
- Analyzes sentiment instantly and updates dashboards dynamically

### 3.Topic Modeling & Sentiment Correlation
- Applies Latent Dirichlet Allocation (LDA)
- Maps dominant topics with associated sentiment trends

## Tools & Technologies
- **Programming Language:** Python
- **NLP & ML:** NLTK, spaCy, scikit-learn, Gensim, BERT
- **Data Streaming:** Twitter API (Tweepy)
- **Visualization:** Plotly, Dash
- **Database:** MongoDB / SQLite
- **Security:** Bandit, SonarQube
- **Version Control:** Git & GitHub

## Results
- Achieved ~85–90% sentiment classification accuracy
- Successfully monitored and visualized real-time sentiment trends
- Identified topic-based sentiment correlations during live events

##Security Practices
- Static code analysis for unsafe functions
- Taint analysis for input validation
- Runtime checks to prevent unsafe command execution
- Followed OWASP secure coding guidelines

## Documentation
- Full project report available in `/docs/Project_Report.pdf`
- Presentation slides included (if available)

## Future Enhancements
- Improve accuracy using RoBERTa / advanced transformers
- Add sarcasm and emoji-aware sentiment detection
- Deploy on cloud platforms (AWS / Azure)
- Extend support to other social media platforms

## Contributors
- K. Haneesh  
- M. Bharath Royal  
- S. Md. Irfan

## License
Academic project – for learning and demonstration purposes

Note: This is an academic capstone project. The repository focuses on system design,
documentation, and conceptual implementation. Code modules can be extended further.
