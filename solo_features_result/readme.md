# title

Confidence plots and ROC-PRC plots for all single features

confidence_graph : 
- X axis : distance between data points and the decision threshold
- Y axis : the accuracy % (average, median, some percentiles) of each of the 20 bins
- The numbers next to the bin averages are the sample size of each bins after the 622*5 runs.

ROC-PRC : self-explanatory, except not an average of the 622*5 runs but just the first training run (so essentially a random one).