# PyTorch Learning Resources

A comprehensive collection of Jupyter notebooks covering PyTorch fundamentals, neural network architectures, optimization techniques, and advanced applications.

## 📋 Table of Contents

- [Fundamentals](#fundamentals)
- [Neural Network Basics](#neural-network-basics)
- [Architectures](#architectures)
- [Training & Optimization](#training--optimization)
- [Advanced Topics](#advanced-topics)
- [Datasets](#datasets)

---

## Fundamentals

### 1. **tensors_in_pytorch.ipynb**
Introduction to PyTorch tensors, basic operations, tensor properties, and manipulation techniques.

### 2. **pytorch_autograd.ipynb**
Deep dive into automatic differentiation, backpropagation, and the autograd system in PyTorch.

---

## Neural Network Basics

### 3. **pytorch_nn_module.ipynb**
Introduction to `nn.Module`, building custom neural network layers and modules.

### 4. **dataset_and_dataloader.ipynb**
Working with PyTorch DataLoaders, custom datasets, and data loading best practices.

---

## Architectures

### 5. **ann_fashion_mnist_pytorch.ipynb**
Artificial Neural Network (ANN) implementation on the Fashion MNIST dataset.

### 6. **cnn_in_pytorch.ipynb**
Convolutional Neural Network (CNN) fundamentals and implementation.

### 7. **cnn_optuna.ipynb**
CNN architecture with Optuna-based hyperparameter optimization.

### 8. **rnn_question_answering_system.ipynb**
Recurrent Neural Network (RNN) applied to question-answering tasks.

### 9. **transfer_learning.ipynb**
Transfer learning techniques using pre-trained models in PyTorch.

---

## Training & Optimization

### 10. **pytorch_training_pipeline.ipynb**
Basic training loop implementation and workflow.

### 11. **pytorch_training_pipeline_using_nn_module.ipynb**
Training pipeline using `nn.Module` for organized model building.

### 12. **pipeline_training_dataloade.ipynb**
Complete training pipeline with DataLoader integration.

### 13. **optimiztion_techniques_on_fminst.ipynb**
Comparison of different optimization algorithms (SGD, Adam, etc.) on Fashion MNIST.

### 14. **hyperparameter_tunning.ipynb**
Systematic hyperparameter tuning and evaluation techniques.

### 15. **training_on_gpu.ipynb**
GPU acceleration, CUDA integration, and distributed training basics.

---

## Advanced Topics

### 16. **MNIST_Digit_Dataset.ipynb**
In-depth exploration of the MNIST handwritten digit classification dataset.

---

## Datasets

### 17. **fmnist_small.csv**
Fashion MNIST subset data in CSV format for reference or alternative data loading methods.

---

## 📚 Learning Path

**Recommended order for beginners:**

1. Start with fundamentals: `tensors_in_pytorch.ipynb` → `pytorch_autograd.ipynb`
2. Learn neural networks: `pytorch_nn_module.ipynb` → `dataset_and_dataloader.ipynb`
3. Build basic models: `pytorch_training_pipeline.ipynb` → `ann_fashion_mnist_pytorch.ipynb`
4. Explore architectures: `cnn_in_pytorch.ipynb` → `rnn_question_answering_system.ipynb`
5. Advanced techniques: `transfer_learning.ipynb`, `training_on_gpu.ipynb`, `hyperparameter_tunning.ipynb`

---

## 🔧 Requirements

- PyTorch
- Jupyter Notebook or JupyterLab
- NumPy, Pandas, Matplotlib (for data visualization)
- Optuna (for hyperparameter tuning notebooks)

---

## 📝 Notes

- All notebooks are self-contained with explanations and code examples
- Datasets used: MNIST and Fashion MNIST
- GPU training examples included for CUDA-enabled systems

---

**Last Updated:** May 2026
