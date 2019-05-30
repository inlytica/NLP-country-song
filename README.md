<h1> AI Country</h1>

Repository for LinkedIn Article:  


"So, who's a fan of '70s country music?  Yeah, me neither.  But, I recently ran across an article in Data Science Central about using a recurrent neural network to generate a new rap song and thought I would give it a try.  Since rap had been done, I started looking for another genre with somewhat predictable lyrics.  (I briefly considered 80's hair ballads but needed a larger set of songs.)  

The rap song was generated using the KNIME platform, but since I am in python every day I went directly to the Keras library.  As usual, data prep[i] and tuning were major pains in the @$$, and even though I used the early stopping callback some overfitting occurred."





Resources:<br>
https://www.datasciencecentral.com/profiles/blogs/ai-generated-rap-songs<br>
https://machinelearningmastery.com/develop-character-based-neural-language-model-keras/<br>


Files:<br>
char_sequences.txt................................Character sequences<br>
lyrics.txt......................................................Transformed Lyrics<br>
lyricsTrain.csv...........................................Lyrics used to train model<br>
mapping.json.........................................              Character to number mapping dictionary<br>
model.units512.es_val_acc.2..............Trained model<br>
modelLyricsHistory.csv........................   Model values history<br>
NLP-country-song.ipynb....................   Jupyter Notebook code<br>
requirements.txt.....................................Package requirements<br>


