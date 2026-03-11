# YouTube Comment Grader

A simple Python tool that fetches comments from a YouTube video and analyzes their sentiment.
The program identifies **positive, neutral, and negative comments** and highlights negative ones.

---

## Features

* Fetch comments from a YouTube video
* Detect sentiment using TextBlob
* Highlight negative comments
* Save results to a CSV file
* Simple and beginner-friendly Python code

---

## Requirements

* Python 3
* TextBlob
* Google API Python Client

Install the required libraries:

```
pip install textblob google-api-python-client
```

---

## Getting a YouTube API Key

1. Go to the Google Cloud Console
2. Create a new project
3. Enable **YouTube Data API v3**
4. Go to **Credentials**
5. Create an **API Key**

Paste the API key into the code:

```
API_KEY = "YOUR_API_KEY"
```

---

## How to Run

1. Clone the repository or download the files.

2. Open a terminal in the project folder.

3. Run the script:

```
python commentgrader.py
```

4. Enter a YouTube video ID when prompted.

Example:

```
https://www.youtube.com/watch?v=G8OprKbgDZM
```

Video ID:

```
G8OprKbgDZM
```

---

## Output

The program prints analyzed comments in the terminal and saves them to a file:

```
comments.csv
```

Example:

Comment: This tutorial is amazing
Grade: Positive
Score: 0.7

Comment: This video is terrible
Grade: Negative
Score: -0.8
⚠ Negative comment detected

---

## Project Structure

```
youtube-comment-grader
│
├── commentgrader.py
├── comments.csv
├── requirements.txt
└── README.md
```

---

## Example Use

This project can be used for:

* YouTube moderation tools
* Sentiment analysis learning
* AI/ML beginner projects
* Data analysis practice

---

## License

This project is open-source and free to use.
