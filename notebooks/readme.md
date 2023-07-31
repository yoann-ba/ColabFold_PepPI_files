# title

In logical order of use : 

- Home_ColabFold_batch_call : the notebook I built based on a mix of ColabFold's base notebook + batch notebook, then re-hooked the install url path to my own branch. Hardcoded a few parameters but every parameter of the CF's run function is precised in the code, just not displayed as a Colab Form parameter (unless very niche/not function-related parameters).
- create_features_from_zips : from every complex.zip file in my Google Drive, compute all confidence- and distance-based features and build a .csv out of them (see data).
- get_msa_from_zip : from the same complex.zip files in Drive, compute all MSA embeddings-based features (vector shape) and save a .npy file out of them (see data).
- model_plots_stats : making models for the transfer task from the features csv, plot the data distribution, run a few different training loops, run confidence plot loops.
- msa_embds_plots_stats : plot various tSNE plots for all MSA embeds-based features.