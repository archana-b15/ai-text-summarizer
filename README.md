# AI Text Summarizer 🤖

An AI-powered text summarization app built with HuggingFace Transformers.
Paste any long text and get a clean, concise summary instantly.

## What it does
- Takes any long text as input
- Uses a pre-trained BART model to understand and compress the text
- Returns a clean summary preserving all key ideas

## Technologies Used
- Python
- HuggingFace Transformers (v4.41.0)
- Google Colab

## How to Run
1. Open the notebook in Google Colab
2. Run all cells in order
3. Paste your long text when prompted
4. Get your summary instantly

## Example
**Input:** 150 word article about text summarization...

**Output:**
Text summarization is essential in today's information-rich 
digital world. Recent advancements in AI have significantly 
improved summarization quality.

## Model Used
`sshleifer/distilbart-cnn-12-6` — A lightweight version of 
Facebook's BART model, trained on CNN news articles.
