# Chess FEN model project
A little project to try and classify whole chess board image into FEN notation.

The dataset that was used:
https://www.kaggle.com/datasets/koryakinp/chess-positions

With smaller batch size got to 99% accuracy under 20 epochs.
Noticed that there are false predictions more between queen and king pieces. Maybe because there are much less queen pieces in training data.