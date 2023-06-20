# ShakesBERT
Final project for EN.601.488 Machine Learning: Deep Learning at JHU

- We collected and cleaned approx. 300MB of English poetry data and wrote data parsing/loading functions in Python.
- We wrote a three-staged (non-sonnet poems --> non-Shakespearean sonnets --> Shakespearean sonnets) train/validation/test pipeline in PyTorch to fine-tune BERT to recover masked words in unseen Shakespearean sonnets.
- The model achieved a top-10 accuracy of 36.73\% and cosine similarity score of 0.6294 compared to 10.46\%/0.3744 at baseline.
- The project won the Intuitive Surgical Best Project Award among 34 competing teams.

Demo: http://shakesbert.com/.
