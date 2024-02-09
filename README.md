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