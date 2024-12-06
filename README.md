# Deep-learning--RESNET-9
Objective

The project involves classifying CIFAR-10 images using ResNet-9, with techniques like data augmentation, batch normalization, and residual blocks implemented using PyTorch.

Dataset:

CIFAR-10: A dataset containing 60,000 32x32 color images in 10 classes. Downloaded and preprocessed (normalized and augmented).

Data Preparation:

Data transformations include normalization with mean (0.4914, 0.4822, 0.4465) and standard deviation (0.2023, 0.1994, 0.2010). Randomized data augmentation applied (e.g., flips, crops). Dataloaders created for efficient batch processing.

Model Architecture: Implemented ResNet-9, which includes: Convolutional layers with batch normalization. Residual blocks to mitigate vanishing gradients. Model optimized for GPU usage.

Training Process:

Optimization: Adam optimizer used with weight decay and gradient clipping. Learning Rate Scheduling: Implemented one-cycle learning rate policy. Training ran for 8 epochs with techniques like learning rate visualization and accuracy plotting. Results:

Achieved a validation accuracy of 90% on the CIFAR-10 dataset. Training and validation losses and accuracies plotted to analyze model performance.

Final model saved as Resnet9-cifar10.pth for future use. it is included in the repository.

Key Takeaways CIFAR-10 dataset is successfully classified using a deep learning approach with a 90% accuracy. The combination of residual learning, batch normalization, and modern optimization techniques ensured efficient training.

