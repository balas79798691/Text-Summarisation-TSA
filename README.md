[Text_Summarization_README.md](https://github.com/user-attachments/files/33029613/Text_Summarization_README.md)
# Text-Summarisation-TSA# Smart Text Summarizer

A Python-based Text & Speech Analysis mini-project that automatically converts lengthy text into a shorter summary.

## Objective

The objective of this project is to reduce the length of a document while preserving its most important information.

## Features

- Accepts lengthy text
- Performs basic text preprocessing
- Uses extractive summarization
- Allows the user to select the number of summary sentences
- Calculates compression/reduction percentage
- Suitable for articles, reports, and notes

## Technologies Used

- Python
- NLTK
- Sumy
- LSA Summarizer
- Regular Expressions

## NLP Technique

The project uses **Latent Semantic Analysis (LSA)** for extractive text summarization.

Instead of generating completely new sentences, the system selects important sentences from the original document.

## How It Works

1. User provides a long passage.
2. The text is normalized.
3. The document is divided into sentences.
4. LSA analyzes the document.
5. Important sentences are selected.
6. The selected sentences form the final summary.
7. The application reports the reduction in text size.

## Example

**Input:**

A long article containing information about artificial intelligence, machine learning, healthcare, education, and responsible AI.

**Output:**

```text
Artificial intelligence is changing many areas of modern life.
Machine learning allows systems to learn patterns from data.
Organizations must also consider privacy, security, fairness, and responsible use.
```

## Requirements

```bash
pip install sumy nltk
```

## Running the Project

Open `Text_Summarization.ipynb` in Google Colab, Jupyter Notebook, or VS Code.

Run the installation and setup cells first, then execute the application section.

## Project Structure

```text
Text-Summarization/
│
├── Text_Summarization.ipynb
└── README.md
```

## Applications

- News article summarization
- Research paper summarization
- Meeting notes
- Report summarization
- Educational notes
- Document processing

## Conclusion

This project demonstrates how extractive Natural Language Processing can reduce lengthy documents into concise summaries while retaining important information.
