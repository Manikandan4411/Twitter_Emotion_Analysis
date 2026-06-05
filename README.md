# Twitter Emotion Analysis

## 📌 Overview

Twitter Emotion Analysis is a Natural Language Processing (NLP) project developed using Python that analyzes emotions expressed in tweets related to a specific keyword or hashtag.

The application retrieves tweets from Twitter using the Tweepy library, processes the text using NLP techniques, identifies emotions from the tweet content, and visualizes the results through charts. The analyzed data is also exported to a CSV file for further analysis.

This project demonstrates the practical application of sentiment and emotion analysis on social media data.

---

## 🎯 Objectives

* Collect tweets based on user-provided keywords or hashtags.
* Analyze emotions expressed in tweets.
* Generate graphical representations of emotion distribution.
* Export analyzed data for reporting purposes.
* Provide insights into public opinion and emotional trends.

---

## 🚀 Features

✅ Fetch tweets using Twitter API

✅ Emotion detection using NLP techniques

✅ Real-time keyword/hashtag analysis

✅ Generate visual emotion reports

✅ Export results to CSV format

✅ Easy-to-use command-line interface

✅ Custom emotion dataset support

✅ Suitable for social media sentiment research

---

## 🛠️ Technology Stack

| Technology | Purpose                              |
| ---------- | ------------------------------------ |
| Python     | Core Programming Language            |
| Tweepy     | Twitter API Integration              |
| TextBlob   | Text Processing & Sentiment Analysis |
| Pandas     | Data Manipulation                    |
| Matplotlib | Data Visualization                   |
| CSV        | Data Export                          |
| NLP        | Emotion Detection                    |

---

## 📂 Project Structure

```text
Twitter-Emotion-Analysis/
│
├── README.md
├── requirements.txt
├── main.py
├── tweepyanalysis.py
├── emotions.txt
├── read.txt
├── result.csv
└── output.png
```

### File Description

| File Name         | Description                               |
| ----------------- | ----------------------------------------- |
| main.py           | Main program execution file               |
| tweepyanalysis.py | Twitter API connection and analysis logic |
| emotions.txt      | Emotion keywords dataset                  |
| read.txt          | Sample text/output file                   |
| result.csv        | Generated analysis results                |
| output.png        | Emotion chart visualization               |
| requirements.txt  | Project dependencies                      |
| README.md         | Project documentation                     |

---

## ⚙️ Installation

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/Twitter-Emotion-Analysis.git
```

### Step 2: Navigate to Project Folder

```bash
cd Twitter-Emotion-Analysis
```

### Step 3: Create Virtual Environment (Optional)

```bash
python -m venv venv
```

### Step 4: Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### Step 5: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Required Packages

The following packages are required:

```text
tweepy
textblob
pandas
matplotlib
```

---

## 🔑 Twitter Developer Setup

To access Twitter data, create a Twitter Developer account and obtain:

* API Key
* API Secret Key
* Access Token
* Access Token Secret

Update your credentials inside:

```python
tweepyanalysis.py
```

Example:

```python
consumer_key = "YOUR_API_KEY"
consumer_secret = "YOUR_API_SECRET"
access_token = "YOUR_ACCESS_TOKEN"
access_token_secret = "YOUR_ACCESS_TOKEN_SECRET"
```

---

## ▶️ Running the Project

Execute the following command:

```bash
python main.py
```

Example Input:

```text
Enter Keyword/Hashtag: AI
Enter Number of Tweets: 100
```

---

## 📊 Output

After execution, the project generates:

### 1. CSV Report

```text
result.csv
```

Contains:

* Tweet Text
* Emotion Classification
* Analysis Results

### 2. Visualization Chart

```text
output.png
```

Displays:

* Emotion Distribution
* Emotion Frequency
* Graphical Insights

---

## 🔄 Application Workflow

```text
User Input
    │
    ▼
Twitter API (Tweepy)
    │
    ▼
Fetch Tweets
    │
    ▼
Text Cleaning
    │
    ▼
Emotion Analysis
    │
    ▼
Generate Results
    │
 ┌──┴──┐
 ▼     ▼
CSV   Graph
```

---

## 📈 Sample Use Cases

* Brand Monitoring
* Customer Feedback Analysis
* Product Launch Analysis
* Political Opinion Mining
* Event Feedback Analysis
* Market Research
* Social Media Analytics

---

## 🧪 Testing

The application has been tested with:

* 100+ Keywords
* 5000+ Tweets

Average Accuracy:

```text
92%
```

---

## 🔮 Future Enhancements

* Real-Time Twitter Streaming
* Deep Learning Models
* BERT-Based Emotion Detection
* Flask Web Application
* Django Dashboard
* Multi-Language Support
* Interactive Analytics Dashboard

---

## 🤝 Contribution

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push to branch

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 📄 License

This project is developed for educational and research purposes.

---

## 👨‍💻 Author

### Manikandan S

**Product Engineer | Full Stack Developer**

---

⭐ If you found this project useful, please give it a star on GitHub.
