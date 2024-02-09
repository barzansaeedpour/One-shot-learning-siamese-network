# One-shot-learning-siamese-network (Facial Verification)

## Description
In this repository, we build a siamese network for facial recognition form scratch, based on the following paper:
- paper link: [Siamese Neural Networks for One-shot Image Recognition](https://www.cs.cmu.edu/~rsalakhu/papers/oneshot1.pdf)

![alt](./files/paper.PNG)

## What is Siamese Nuerual Network:
![alt](./files/architecture.PNG)
![alt](./files/architecture2.PNG)

A Siamese neural network, also known as a twin neural network, is an artificial neural network architecture that operates on two different input vectors using the same weights. Its primary purpose is to compute comparable output vectors for these inputs. Here are the key points about Siamese networks:

- **Architecture**:
  - Consists of two identical subnetworks (twins) with shared weights.
  - Each twin processes a different input vector.
- **Comparison and Output**:
  - Twins compute output vectors for their inputs.
  - One output vector is precomputed (baseline).
  - The other output vector is compared using a distance function.
- **Applications**:
  - Face recognition, signature verification, and more.
- **Learning**:
  - Triplet loss or contrastive loss for training.

Siamese networks enable similarity comparisons between input pairs.

## Training:

As 

## Code (notebook)

Open the notebook in colab:
[colab](https://)


## Dataset
We need three type of data to train and test our siamese network:

- Anchor images: images of our face
- Positive images: also images of our face
- Nagativa images: random images of other people's face 
[download](http://vis-www.cs.umass.edu/lfw/lfw.tgz)

for the Anchor and Positiva images: you can use the python code in  ``` take_picures.py ``` file.

You can also use the following link to dowload all in once: 
[download](https://drive.google.com/drive/folders/1-4KAStGQgStFQD4IVU-dwf6GQXw-HS88?usp=sharing) 

