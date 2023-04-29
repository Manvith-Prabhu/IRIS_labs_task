# IRIS_labs_task
I tried to summarize in 2 different ways:

1) My first approach was to try to make a model myself and training it so that it can summarize the text. 
Since creating transformers is difficult, I thought of creating some Attention model. Later I found that Birectional LSTM can be a good choice.
This idea mainly came from a kaggle notebook which had a pictorial representation of used LSTM for text summarization which was easier for me to understand.
So i tried to copy it. I preprocessed the text and ran the model on the text. However the performance was very bad. I also generated rouge score taking the abstract given in kaggle dataset as reference
![Model](https://github.com/Manvith-Prabhu/IRIS_labs_task/blob/main/model_image.png)
