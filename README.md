# Multi-modal Music Genre Classification (MGC) using VAEs

This repository contains the implementation of a **Variational Autoencoder (VAE)** and a **Conditional VAE (CVAE)** framework for unsupervised music genre classification on the **GTZAN dataset**. By integrating **Mel-spectrograms** with **TF-IDF lyric embeddings**, this project bridges the "semantic gap" in audio analysis through multi-modal feature fusion.

## Key Features

* **Multi-modal Fusion:** Combines audio MFCCs () with semantic text features ().
* **Latent Space Disentanglement:** Utilizes -annealing to organize the latent manifold for better cluster purity.
* **Probabilistic Clustering:** Implements a CVAE architecture to condition audio representations on lyrical content.
* **Quantitative Evaluation:** Benchmarked using Silhouette Score, NMI, and ARI metrics.

##  Tech Stack

* **Language:** Python
* **Deep Learning:** PyTorch / TensorFlow
* **Audio Processing:** Librosa
* **Machine Learning:** Scikit-learn

##  Results

Our Hybrid Fusion approach demonstrated a **400% improvement** in Silhouette Score compared to audio-only baselines, proving that lyrical data successfully disentangles overlapping musical genres like *Rock* and *Blues*.

##  How To RUn
* Download the notebook [here](https://drive.google.com/file/d/1zT0pXp4gN4whciFamR0dTTUgJ3YEVNag/view?usp=drive_link)
* Download the audio (Data\audio)
* Download the zipped lyrics (Data\lyrics) and unzip
* Run the notebook with these training data

##  Keywords

`Music Information Retrieval` `VAE` `Multi-modal Learning` `GTZAN` `Representation Learning` `Latent Space` `Feature Fusion` `Unsupervised Learning` `BRACU` `CSE425` `425` `PROJECT` 
