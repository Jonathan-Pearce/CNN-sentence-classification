Packages Used: nltk, string, re, io, random, numpy, matplotlib.pyplot, tensorflow, keras, sklearn
Also used: Google Colab notebook for CNN-rand replication

***Replication Procedure***

1) sklearn models

2)CNN-rand  Replication (Filename: 551_cnn.ipynb)
Ensure desired dataset is loaded into environment
Run Code Blocks 1-5
Run Code Block 6,7 or 8 depending on which data set
--> 6 = MR, 7 = Subj, 8 = MPQA
Run Code Block 9-19
Run Code Block 20 and 21 to generate visualization(s) in report
Find the first epoch in which the network's validation accuracy does not increase for the next 5 epochs. Change the first line of code in Block 23 to load in that network save file
Run Code Block 23 (will provide test accuracy)
Run Code Block 24 to generate model summary (will provide number of parameters)
