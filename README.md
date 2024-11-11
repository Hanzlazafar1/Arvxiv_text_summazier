# AI Paper Summarizer

A Python-based project to fetch recent research papers from [arXiv](https://arxiv.org/) and generate concise summaries using a Transformer-based model.

## Overview
This tool automates the process of finding and summarizing the latest research papers in the fields of AI and Machine Learning. It:
1. Retrieves papers from arXiv based on specified keywords.
2. Uses the powerful `facebook/bart-large-cnn` model to generate concise and informative summaries for each paper.

The result is a simple, efficient way to stay up-to-date with recent advancements in AI, without needing to read through lengthy abstracts.

## Features
- **Automatic Paper Retrieval**: Retrieves papers from arXiv by keywords like "artificial intelligence" or "machine learning."
- **Text Summarization**: Utilizes a transformer-based model to generate a brief summary of each paper's abstract.
- **User-Friendly Output**: Displays paper titles, authors, categories, and summarized abstracts for easy review.

## Setup

### Requirements
- Python 3.x
- Required Python libraries:
  - `arxiv`
  - `transformers`
  - `pandas`

Install dependencies with:
```bash
pip install arxiv transformers pandas
```

### Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/ai-paper-summarizer.git
    cd ai-paper-summarizer
    ```

2. **Run the script**:
    ```bash
    python summarize_papers.py
    ```

3. **Check the Output**:
   The script will fetch the latest AI-related papers, summarize them, and display the titles, authors, categories, and summaries in a tabular format.

## Example

Here’s an example of the summarized output for a paper:
| Title                               | Authors           | Category    | Summary                                   |
|-------------------------------------|-------------------|-------------|-------------------------------------------|
| Recent Advances in AI               | A. Author, B. Author | cs.AI | This paper discusses new approaches in AI... |

## Model Information
We use the `facebook/bart-large-cnn` model from the [Transformers library by Hugging Face](https://huggingface.co/transformers/), known for its effectiveness in text summarization.

## Future Plans
- Add multi-category search support.
- Implement sentiment analysis for summarized content.

---

## License
This project is licensed under the MIT License.

---

Enjoy staying informed with the latest in AI research!
