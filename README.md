# Text Summarizer with AI

This project provides an AI-powered text summarization tool capable of generating concise summaries from larger texts. Leveraging both traditional NLP techniques and advanced machine learning models, this tool aims to enhance readability and information retention for users. The implementation is based on Python, utilizing the NLTK library for preprocessing and the Hugging Face Transformers library for model-based summarization.

## Features

- **Basic Summarization:** Uses frequency analysis of bigrams to score and extract the most relevant sentences from the input text.
- **Model-Based Summarization:** Employs a pre-trained summarization model from Hugging Face's Transformers library for generating summaries, suitable for longer or more complex texts.
- **Support for Text Files:** Besides direct text input, this tool can also summarize content directly from text files, making it versatile for different use cases.

## Installation

Before running this tool, ensure you have Python installed on your system. This project requires Python 3.6 or later.

1. **Clone the repository:**

```bash
git clone [https://github.com/yourgithubusername/text-summarizer-with-ai.git](https://github.com/JustinRivera2018/Text-Summarizer)
cd text-summarizer-with-ai
```

2. **Install required libraries:**

```bash
pip install -r requirements.txt
```

This will install all necessary dependencies, including NLTK and Transformers.

3. **Download NLTK data:**

The script automatically downloads necessary NLTK data (punkt and stopwords) upon first run. However, you can manually download them using the following Python commands:

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## Usage

Run the script from the command line:

```bash
python text_summarizer.py
```

You will be prompted to choose between basic summarization, model-based summarization, or summarizing text from a file. Follow the on-screen instructions to proceed.

- **Option 1:** Basic summarization using NLTK.
- **Option 2:** Model-based summarization using Hugging Face's Transformers.
- **Option 3:** Summarize text from a specified file.

## Requirements

- Python 3.6+
- NLTK
- Transformers by Hugging Face

## Contributions

Contributions are welcome! If you'd like to improve the project or suggest features, feel free to fork the repository and submit a pull request.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

---


