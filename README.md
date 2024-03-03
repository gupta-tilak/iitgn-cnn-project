I have made a preliminary model for testing the structure of the code. Training a new model from scratch requires lot of computational efficiency and time for such high quality images. 
VGG16 for instance for trained for days on one of the best intel processor (NEON).

The code describes my approach for the classification of the animals.

5 Class Classification will outperform One Vs Rest because the data has a significant imbalance when the training the model on OvR architecture and would also take a lot more time for prediction.
Provided, we have a better dataset targeted specifically for OvR this might better results. 

The currect 5 class model will eventually become much better if it is trained for higher epochs (~150-200).
Currently, only 5 epochs have been done and it took around 1.5 hours for me to train the model.
