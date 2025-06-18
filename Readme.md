
---

# YouTube Comment Scraper & Sentiment Analyzer

## 📖 Project Description

A Python tool that scrapes YouTube video comments, analyzes sentiment (positive, negative, neutral) using VADER sentiment analysis, and emails CSV reports to the user automatically.

## ✨ Features

* Scrapes comments from any public YouTube video
* Performs sentiment analysis using VADER
* Generates CSV reports:

  * Full Comments
  * Positive Comments
  * Negative Comments
* Emails reports automatically via Gmail SMTP
* Simple and customizable

## 🛠️ Libraries Used

* `googleapiclient` — for accessing YouTube API
* `vaderSentiment` — for sentiment analysis
* `smtplib` — for sending emails
* `email` — for creating email content with attachments
* `mimetypes` — for handling file types

## ⚙️ How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python your_main_script.py
   ```

4. The script will:

   * Scrape comments
   * Perform sentiment analysis
   * Save CSV files
   * Email results

## 💻 Prerequisites

* Python 3.x
* YouTube Data API key
* Gmail account (for sending emails — App Password recommended)

## 🚀 Future Improvements

* Add GUI for ease of use
* Add more advanced NLP for better sentiment accuracy
* Deploy as a web app

---


