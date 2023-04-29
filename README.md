# IRIS_labs_task
I tried to summarize in 2 different ways:

1) My first approach was to try to make a model myself and training it so that it can summarize the text. 
Since creating transformers is difficult, I thought of creating some Attention model. Later I found that Birectional LSTM can be a good choice.
This idea mainly came from a kaggle notebook which had a pictorial representation of used LSTM for text summarization which was easier for me to understand.
So i tried to copy it. I preprocessed the text and ran the model on the text. However the performance was very bad. I also generated rouge score taking the abstract given in kaggle dataset as reference
![model_image](https://user-images.githubusercontent.com/97300224/235286724-a4e93749-6bb5-4d9b-843e-99af9bcec47c.png)

2) Since the results were very bad in first case I decided to go with a pretrained transformer this time.
As simpleT5 was built on tensorflow I decided to use it.
This time I did not preprocess. I just made required changes to suite use of T5 and generated results. Then calculated the ROUGE scores.
