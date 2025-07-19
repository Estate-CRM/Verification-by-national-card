# AI-Powered Face Matching System Using ID and Live Image

This project implements a facial verification system using deep learning. The goal is to verify whether two face images—one extracted from a national ID and another from a live or external source—belong to the same person.

It utilizes `facenet-pytorch` for face detection and embedding extraction, and measures similarity using cosine distance.

## Features

- Detects faces using MTCNN.
- Extracts 512-d embeddings using InceptionResnetV1 (pretrained on VGGFace2).
- Compares two images using cosine similarity.
- Automatically determines identity match based on a threshold.

## Technologies Used

- Python 3
- facenet-pytorch
- OpenCV
- PIL (Pillow)
- PyTorch
- NumPy

## Dataset

The notebook uses two images:
- One national ID photo.
- One real or test image to compare.

You can replace them with your own images inside the notebook.



