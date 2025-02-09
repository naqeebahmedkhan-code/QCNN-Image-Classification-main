# QCNN-Image-Classification

Image classification is a core task in computer vision, which involves categorizing
images into predefined categories based on their visual content. Traditional approaches
using convolutional neural networks (CNNs) have achieved significant success in this
field due to their ability to capture spatial hierarchical structures in image data. This
report explores the application of quantum convolutional neural networks (QCNNs) to
image classification by studying several papers and reproducing the results. This project
trained and tested several proposed QCNNs to evaluate their performance and compare
with classical CNNs, using the MNIST dataset as a benchmark. This research used a
quantum simulator provided by IBM and the PennyLane platform, which allowed for a
comprehensive comparison of these architectures in a controlled environment.

Many researchers have different definitions of quantum convolutional neural networks.
First, a novel quantum machine learning model inspired by classical CNNs has been introduced
[1]. They proposed a fully parameterized quantum circuit (PQC) architecture
and demonstrated its success for some quantum many-body problems. Not long after,
Kerenidis et al. proposed a quantum algorithm for applying and training deep CNNs with
the same name of QCNN, which mimics the behavior of a Quantum CNN [2]. In addition,
others have proposed a new type of transformational layer called a quantum convolution,
or quanvolutional layer [3]. In this project, we mainly study the above algorithms, quantum
circuits and quantum convolutional layers.


REFRENCES:
[1] Iris Cong, Soonwon Choi, and Mikhail D. Lukin. Quantum Convolutional Neural
Networks. 15(12):1273–1278.
[2] Iordanis Kerenidis, Jonas Landman, and Anupam Prakash. Quantum Algorithms for
Deep Convolutional Neural Networks.
[3] Maxwell Henderson, Samriddhi Shakya, Shashindra Pradhan, and Tristan Cook.
Quanvolutional neural networks: Powering image recognition with quantum circuits.
2(1):2.
