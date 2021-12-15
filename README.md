# Capstone-CLS
CLS (Eng to Kannada) Project Abstract:

The application of Natural Language Processing to summarization and machine translation has been accelerating in the past years. One of them is Cross-Lingual Summarization (CLS), which produces a summary for an input document in a different language.Current methods divide the CLS into two methods: summarization(Abstractive or Extractive) and translation.CLS helps people understand an article’s gist in an unfamiliar language by translating its summary to their familiar language.

Although there has been tremendous progress in summarization in recent years, most of the research focuses on monolingual summarization because of the lack of high quality multilingual resources.While there has been a few studies to address the lack of resources for cross-lingual summarization , the datasets employed are very limited in size, especially for low resource languages like Kannada.. Here we are implementing CLS on English news articles to obtain Kannada summaries. This would help the native Karnataka people who don’t speak English. Traditional CLS methods are pipeline-based. Either it involves summarization and then translation or vice versa. Here we are implementing summarization and then translation (‘late translation’). Since CLS work has been less explored, we are implementing it on news articles in english to summarize and then translate to kannada.

Code Execution:

Open File name → Testing_Pegasus_LSTM_CLS.ipynb in Google Colab
Click on links mentioned for Dataset,Fasttext Embedding, Checkpoint in “Testing_Pegasus_LSTM_CLS.ipynb” file and add shortcut for each file to your Google Drive (/Mydrive)
Run all the cells
Give access to mount the drive to Google colab.
Enter input text(i.e. the news article to be summarized) when respective cell is reached.
The output Kannada summary will be printed.
