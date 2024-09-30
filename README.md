# Sentiment-Analysis

This my attempt on doing a Sentiment Analysis on an Amazon review dataset with pre-trained models such as:<br>
1. VADER model,
2. roBERTa model, and also
3. Huggingface Pipeline

From the code provided, both VADER model and roBERTa have a scoring formula on determining positive or negative reviews, hence some negative reviews that contains a lot of 'positive' marked words are marked as positive, but not for huggingface's pipeline. I also find it interesting that most models are still unable to detect sarcasm resulting on some reviews being marked as 'positive'. This is just my attempt on using the pre-trained models and for my further works, I will try to do fine-tuning on both VADER and roBERTa with the dataset provided.

Dataset link : [Amazon Fine Food Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
