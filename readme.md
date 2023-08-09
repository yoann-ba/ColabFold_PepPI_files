# ColabFold PepPI files

Repository to store files (code + images + misc.) for my project of using ColabFold v1.5.2 for PepPI prediction titled "Fast and precise PepPI predictions with ColabFold 1.5 and AlphaFold-Multimer v3".

- Paper : pdf in this repo, or [Google Drive Link to Paper](https://drive.google.com/file/d/1Xpoc-DleggcrFVOVCe4rxhqbAIQGe7Mm/view?usp=sharing)
- Supplementary : pdf in this repo or [Google Drive Link to Supplementary](https://drive.google.com/file/d/19R4bybsyg4HVCO0euEBLGTgZEeiiv2nv/view?usp=sharing)
- Video : [not made yet]

----

## Abstract

ColabFold 1.5, based on AlphaFold-Multimer v3, allows for fast and precise transfer to prediction of Peptide-Protein Interactions, with 98% average Precision for 48% average Recall with only 2 seeds. Many features are tested, based both on confidence metrics and the distogram, as well as simple ML models. A transfer confidence metric is studied to support the transfer task. Features are also created on the MSA embeddings to test their use for data clustering, notably finding that a sequence-analog peptide-protein split still persists at the end of the AlphaFold pipeline.

----

## Repo structure

- data : input sequences, transfer features .csv, MSA embeddings features .npy
- notebooks : the notebooks used (I started using Colab due to CF's GPU VRAM cost, then had to for a moment due to my PC having issues, and then decided to keep going with full Colab until the end. I don't quite recommand doing a full project like this, I'm glad to be back on my local spyder now.)
- paper_figures : full size resolution of the images in the paper
- solo_features_distribution : data distribution plot for each transfer feature
- solo_features_result : confidence plot, ROC curve and PRC for each transfer feature (used as a model with the decision threshold calibration)
- msa_embeds : all the tSNE plots based on the features built on the MSA embeddings

----

## Citing

If you find this work useful, please consider citing:

    @article{ColabFold_PepPI,
	author = {Battu, Yoann}, 
	title = {Fast and precise PepPI predictions with ColabFold 1.5 and AlphaFold-Multimer v3}, 
	journal = {Preprint}, 
	year = {2023}
    }

Or looking at this work's references at the end of the main pdf.