# Sentiment Analysis Project

This project leverages advanced Natural Language Processing (NLP) models for sentiment analysis, making it adaptable for diverse applications such as Amazon reviews, Google Map reviews, and restaurant reviews, etc. The implementation includes BERT-based models for accurate sentiment scoring and an Extractive Summarization model for generating concise and informative summaries of Youtube videos.

## Models Used

1. **BERT-Based Sentiment Analysis:**
   Utilizing BERT-based models to provide precise and context-aware sentiment scores.

2. **Extractive Summarization:**
   Employing an Extractive Summarization model to generate meaningful summaries by extracting key sentences.

## Dependencies

Make sure you have the following dependencies installed:

- [transformers](https://github.com/huggingface/transformers)
- [summarizer](https://github.com/dmmiller612/bert-extractive-summarizer)
- [tensorflow](https://www.tensorflow.org/)
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [google-api-python-client](https://pypi.org/project/google-api-python-client/)
  
You can install these dependencies using the following:

```bash
pip install transformers summarizer tensorflow numpy pandas google-api-python-client
```

## Usage

1. **Set up YouTube API Key:**
   Obtain a YouTube Data API key from the [Google Cloud Console](https://console.cloud.google.com/), and replace `'YOUR_YOUTUBE_API_KEY'` in the code with your actual API key.

2. **Specify the YouTube Video:**
   Modify the `youtube_video_id` variable with the ID of the YouTube video for which you want to analyze comments.

3. **Run the Jupyter Notebook:**
   Execute the provided Jupyter Notebook to perform sentiment analysis, calculate the overall sentiment score, and generate an extractive summary.

```bash
jupyter notebook main.ipynb
```

4. **View Results:**
   The notebook will display individual sentiments, overall sentiment score, and an extractive summary for the YouTube comments.

## Example
- Video Title: My YouTube Setup: How I Make Videos with an iPhone - Starting a YouTube Channel!
- Video Link: [YouTube Video](https://www.youtube.com/watch?v=wLsJXKuJUZ4)