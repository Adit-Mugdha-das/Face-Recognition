# Face Recognition with FaceNet

This project implements a face recognition system using a pre-trained FaceNet model to perform identity verification based on face images.  
It is part of **Week 4 (Course 4: Convolutional Neural Networks)** from the **Deep Learning Specialization** by **Andrew Ng** on Coursera.

---

## Description

In this assignment, a pre-trained FaceNet model is used to generate embeddings for face images. These embeddings are compared using distance metrics to determine identity matches.  
The project includes:

- Building a face recognition pipeline
- Generating embeddings for input face images
- Verifying and recognizing individuals based on similarity thresholds
- Using triplet loss training concepts
- Visualizing face recognition results

---

## Important Note

Due to file size limitations, the pre-trained FaceNet model directories (`keras-facenet_tf23/` and `keras-facenet-h5/`) have been **removed** from this repository.

**To reproduce the results:**
- Download the FaceNet model files from the following repository:  
  [https://github.com/nyoki-mtl/keras-facenet](https://github.com/nyoki-mtl/keras-facenet)
- Follow the setup instructions to load the model weights.
- Place the downloaded models into the expected directory structure or modify the notebook paths accordingly.

---

## Files and Folders Included

- `Face_Recognition.ipynb` — Main Jupyter notebook
- `fr_utils.py` — Utility functions for face image processing
- `inception_blocks_v2.py` — Inception model blocks used by FaceNet
- `nn4.small2.v1.h5` — Sample pre-trained model file
- `images/` — Sample face images
- `datasets/` — Directory structure for enrolled identities
- `LICENSE` — License file

---

## Key Concepts Covered

- Face embedding generation using deep learning
- Triplet loss and metric learning
- Face verification vs face recognition
- Distance-based identity matching
- Pre-trained model usage for feature extraction

---

## External Resources

- Pre-trained FaceNet repository:  
  [https://github.com/nyoki-mtl/keras-facenet](https://github.com/nyoki-mtl/keras-facenet)

---

## Course Information

This project is part of:  
[Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
Instructor: **Andrew Ng**  
Course 4: **Convolutional Neural Networks**  
Week 4: **Face Recognition with FaceNet**

---

## License

This repository is created for educational and portfolio purposes only.  
It should not be used for direct assignment submission.

---
