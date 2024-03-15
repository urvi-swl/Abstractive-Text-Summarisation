# Abstractive-Text-Summarisation
# Abstractive Text Summarization with Word Sense Disambiguation and Seq2Seq Model

## Introduction
This repository presents an Abstractive Text Summarization model incorporating Word Sense Disambiguation (WSD) using WordNet and employing a Seq2Seq architecture.

## Overview
The repository encompasses the following components:

1. **Data Preprocessing:**
   - Employing the CNN/Daily Mail dataset for training purposes.
   - Implementing WSD using WordNet to disambiguate word senses in the text.

2. **Model Architecture:**
   - Incorporating a Seq2Seq model for abstractive text summarization.
   - Utilizing an Encoder-Decoder architecture with LSTM layers.

3. **Tokenization and Padding:**
   - Tokenizing and preprocessing the text data.
   - Converting text to sequences and padding sequences to a specified length.

4. **Training:**
   - Compiling the model using the RMSprop optimizer and sparse categorical crossentropy loss.
   - Training the model on the provided dataset for a specified number of epochs.

5. **Model Saving and Loading:**
   - Including functions to save and load both the preprocessed texts and the trained Seq2Seq model.

6. **Summarization Function:**
   - Defining a function to generate abstractive summaries for input articles.

## Instructions
To utilize this code, follow these steps:

1. Install necessary libraries: Ensure the required dependencies (`tensorflow`, `nltk`, `datasets`) are installed by running the provided installation commands.

2. Run the notebook: Execute the notebook `Abstractive_Text_Summarisation_with_wsd&seq2seq_model.ipynb` to train the model and conduct text summarization.

3. Save and Load Model: The code includes functions to save and load both preprocessed texts and the trained model. Customize the paths according to your preferences.

4. Summarize Text: Utilize the `summarize_text` function to generate abstractive summaries for input articles.

## Example Usage
```python
input_article = '''[Your input article here]'''
summary = summarize_text(input_article)
print("Generated Summary:", summary)
```

## References
- [CNN/Daily Mail Dataset](https://huggingface.co/datasets/cnn_dailymail)
- [WordNet](https://www.nltk.org/howto/wordnet.html)

## Author
Urvi Siwal
