# CVPR

To analyze the CIFAR-10 dataset, this KNN code implements the k-Nearest Neighbors (k-NN) algorithm. It reads and stores the images in the training directory as image arrays with their corresponding class labels in a list named TRAIN_DATA. The list is shuffled randomly, and a sample of 50 images along with their labels are displayed. The code then splits the shuffled data into 5 folds, using one fold for validation and the remaining 4 for training. It computes accuracy for different values of k (1, 3, 5, 7, 9) using two distance metrics (L1 and L2), and records the average accuracy across the 5 folds for each k value. Ultimately, it plots the average accuracies for both L1 and L2 distances.
