
# AlexNet in PyTorch

AlexNet is one of the most influential convolutional neural networks (CNNs), introduced by Alex Krizhevsky, Ilya Sutskever, and Geoffrey Hinton in the groundbreaking paper titled **"ImageNet Classification with Deep Convolutional Neural Networks"** at NeurIPS 2012. It played a pivotal role in popularizing deep learning by achieving a significant performance improvement on the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) 2012.

---

## 🧠 About AlexNet

- Introduced in 2012
- Won the ImageNet competition by a large margin
- Comprises 5 convolutional layers, 3 fully connected layers, ReLU activations, max-pooling, and dropout
- Utilized GPUs for training long before it became standard

---

## 📐 AlexNet Architecture (Simplified Version)

![AlexNet Architecture](https://github.com/povashraful/Research_paper_implementation/blob/main/AlexNet/model_arch_simplified.png)

*Image source: [Medium](https://medium.com/@abhishekjainindore24/deep-learning-architecture-2-alexnet-8018f7640161)*

---

## 📄 Original Paper
- Title: [ImageNet Classification with Deep Convolutional Neural Networks](https://proceedings.neurips.cc/paper_files/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
- Authors: Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton
- Conference: NeurIPS 2012

---

## 💻 Implementation

This repository includes a clean PyTorch implementation of AlexNet.

🔗 [Click here to view the implementation code](https://github.com/povashraful/Research_paper_implementation/blob/main/AlexNet/Implementing_AlexNet_using_PyTorch.ipynb)

---

## ℹ️ Notes

- The model expects input size of `(3, 227, 227)`
- You can modify the output layer (`output_classes`) to suit your dataset (e.g., 10 for CIFAR-10)
- Includes weight initialization and model summary via `torchinfo`

---

## ⭐️ Contributions & Feedback

Feel free to fork the repository, submit issues, or improve the code. If you find it useful, please consider starring the repo!
