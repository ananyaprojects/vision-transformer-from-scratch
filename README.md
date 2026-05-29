# Vision Transformer (ViT) from Scratch

A deep learning project implemented in PyTorch that builds, trains, and evaluates a **Vision Transformer (ViT)** for image classification from scratch. This project is a practical application of the groundbreaking research paper: *"An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale"*.

## Project Overview
Unlike traditional Convolutional Neural Networks (CNNs), the Vision Transformer applies the standard Transformer architecture (originally designed for text and NLP tasks) directly to images. By flattening image patches and treating them like words in a sentence, the model utilizes Self-Attention mechanisms to learn spatial relationships across the entire image.

## Architecture & Process Flow
The project follows a structured, step-by-step deep learning pipeline:
1. **Dataset Loading:** Prepares image data for classification.
2. **Patch Embedding:** Breaks input images down into small non-overlapping patches (e.g., 16x16 pixels) and projects them into linear embeddings alongside learnable position embeddings.
3. **Transformer Encoder:** Passes the sequence of patch embeddings through Multi-Head Self-Attention (MSA) blocks and Multi-Layer Perceptrons (MLP).
4. **MLP Head:** An extra classification layer mapping the Transformer output to the final target classes.
5. **Vision Transformer Class:** Assembles all the subcomponents into a unified, modular model class.
6. **Training Loop:** Trains the model using optimization algorithms and tracks the loss over epochs.
7. **Validation & Accuracy:** Benchmarks model performance on unseen data.
8. **Prediction:** Runs inference to classify single test images.

## Project Details
* Each image patch is transformed into a **768-dimensional** vector space representation to serve as the token embeddings for the transformer encoder.

## Technologies Used
* **Python 3**
* **PyTorch** (Deep Learning Framework)
* **Torchvision** (For handling images and datasets)
* **Matplotlib / NumPy** (For data visualization and transformations)

## How to Run
1. Go to your GitHub repository dashboard in the browser.
2. Click on the `Copy_of_DEEP_LEARNING_VIT_.ipynb` notebook.
3. Click the **Open in Colab** badge (if available) or download and run it in Google Colab / your favorite cloud environment with a GPU.
