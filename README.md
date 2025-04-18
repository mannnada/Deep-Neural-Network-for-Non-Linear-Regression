# **Deep Neural Network for Non-Linear Regression**

## **Overview**
This repository contains multiple implementations of a **3-layer deep neural network** for non-linear regression using **NumPy, PyTorch, PyTorch Lightning, and TensorFlow**. Each implementation follows the **SOLID principles** and adheres to best coding practices.

Additionally, the repository includes:
- 📌 **Colab notebooks for each implementation**
- 📌 **Detailed explanations of each Colab file**
- 📌 **A video walkthrough of the code and output**
- 📌 **Proper documentation for all files**
- 📌 **Publicly accessible GitHub repository with all files**

---

## **Project Structure**

### **1️⃣ From Scratch Implementations**
- ✅ **NumPy Only (Manual Backpropagation)**
  - Implements a **3-layer deep neural network** without any deep learning library.
  - Uses **manual gradient computation** with **chain rule-based backpropagation**.
  - **Colab Notebook**: https://colab.research.google.com/drive/16P6ZrvK3OCUlPCJLlwGscpjsRjWvJP0q?usp=sharing

- ✅ **PyTorch Without Built-in Layers**
  - Implements a 3-layer neural network using **only tensor operations** (no PyTorch built-in layers).
  - **Colab Notebook**: https://colab.research.google.com/drive/1U9eaEZnEevvNVSAQmlW1ypS6IvmZkOJe?usp=sharing
- ✅ **TensorFlow Without High-Level API**
  - Implements the network using **low-level TensorFlow** operations (without `tf.keras` layers).
  - **Uses `tf.einsum` instead of matrix multiplication** for weight updates.
  - **Colab Notebook**: https://colab.research.google.com/drive/1XvghOtQ5tgQifWIu_wjEyBP1LdPetdQJ?usp=sharing
---

### **2️⃣ Framework-based Implementations**
- ✅ **PyTorch (Using Built-in Layers & Modules)**
  - Implements the network using **PyTorch modules (`torch.nn`) and `autograd` for backpropagation**.
  - **Colab Notebook**: https://colab.research.google.com/drive/1wCMA8Ztgzc0RW6xRykILchBhUYLt2waY?usp=sharing
- ✅ **PyTorch Lightning Implementation**
  - Implements the model using **PyTorch Lightning** for better modularity and training efficiency.
  - **Colab Notebook**: https://colab.research.google.com/drive/1d28q6X1Bz2oHkq0zUeIrKQChoHO5ncPO?usp=sharing

- ✅ **TensorFlow Functional API**
  - Uses the **Functional API** to build a flexible and reusable model.
  - **Colab Notebook**: https://colab.research.google.com/drive/1wpZnzFaVlxcU4PJJKn-sGesg3KpW_xtM?usp=sharing

- ✅ **TensorFlow Using Built-in Layers**
  - Implements the model using **`tf.keras.Sequential` with built-in layers**.
  - **Colab Notebook**: https://colab.research.google.com/drive/1wpZnzFaVlxcU4PJJKn-sGesg3KpW_xtM?usp=sharing

- ✅ **TensorFlow High-Level API (Keras)**
  - Implements the model using **high-level Keras API** for simplicity.
  - **Colab Notebook**: 

---

## **3️⃣ Additional Requirements & Features**
✅ **Synthetic Data Generation**
- The dataset is generated using a **3-variable non-linear equation**.
- Includes **4D visualization** of the data.
- **Colab Notebook**: [Synthetic Data Generation & 4D Plot]

✅ **Code Walkthrough Video**
- A **detailed video** explaining the main code sections.
- Covers **GitHub structure, Colab walkthrough, and final output**.
- 📺 **YouTube Link**: [Watch the Full Code Walkthrough]

