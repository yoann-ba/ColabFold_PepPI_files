# ColabFold PepPI files

Repo to store files (code + images + misc.) for my project of using ColabFold v1.5.2 for PepPI prediction.

Paper : [link coming]
Supplementary : [link coming]
Video : [not made yet]

----

- data : input sequences, transfer features .csv, MSA embeddings features .npy
- notebooks : the notebooks used (I started using Colab due to CF's GPU VRAM cost, then had to for a moment due to my PC having issues, and then decided to keep going with full Colab until the end. I don't quite recommand doing a full project like this, I'm glad to be back on my local spyder now.)
- paper_figures : full size resolution of the images in the paper
- solo_features_distribution : data distribution plot for each transfer feature
- solo_features_result : confidence plot, ROC curve and PRC for each transfer feature (used as a model with the decision threshold calibration)
- msa_embeds : all the tSNE plots based on the features built on the MSA embeddings
