# AI-Powered Job Matcher

This project is an AI-powered job matching tool that takes a user bio or skill set as input and finds the most relevant job description from a predefined list using semantic similarity.

## 🚀 Features

- Uses the `sentence-transformers` library to convert text into embeddings.
- Computes cosine similarity to find the best job match.
- Open-source and easy to customize.

## 💡 How It Works

1. User inputs their bio/skills.
2. The model converts the bio and job descriptions into embeddings.
3. Cosine similarity scores determine the closest matching job.
4. The tool outputs the best job match along with similarity scores.

## 🔧 Usage

```bash
pip install sentence-transformers
python job_matcher.py
