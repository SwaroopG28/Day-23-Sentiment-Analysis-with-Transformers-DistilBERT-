# Sentiment Analysis with Transformers (DistilBERT)

## **Overview**
This project demonstrates how to perform **sentiment analysis** using a pre-trained **DistilBERT** model from Hugging Face's Transformers library. DistilBERT is a smaller, faster, and efficient version of BERT that can classify text into sentiments such as **positive** or **negative**.

---

## **How It Works**
1. **Pre-trained Model**:
   - The project uses the `distilbert-base-uncased-finetuned-sst-2-english` model, fine-tuned on the **SST-2 dataset** for binary sentiment classification.
2. **Pipeline**:
   - Hugging Face's `pipeline` simplifies the entire workflow by handling tokenization, model inference, and decoding the results.
3. **Sentiment Analysis**:
   - Given an input sentence, the model predicts whether the sentiment is **positive** or **negative**, along with a confidence score.


