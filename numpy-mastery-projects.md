# 🔢 NumPy Mastery Projects 

**Author:** \[JAY GOPAL DEY] 
**Learning Path:** Preparing for EPFL + FAANG Internship
**About me: I am a tech enthusiast dedicated to find my own passion in this overcrowded world so i start this AI/ML journey and i think this works.

---

## 📚 Projects Covered:

✅ 3D Array Manipulation & Reshape
✅ Vectorized Math Functions
✅ Image Preprocessing Pipeline
✅ Feature Engineering for ML
✅ Simulated Neural Network Dense Layer with ReLU

---

## 👨‍💻⚙️ Technologies:

* Python
* NumPy
* Matplotlib

---

## ✒️ Project Highlights:

### 1️⃣ 3D Array Manipulation

```python
thrd_arr = np.random.randint(1, 100, size=(10, 4, 5))
thrd_arr = np.swapaxes(thrd_arr, 2, 1)
thrd_arr = thrd_arr.reshape(thrd_arr.shape[0], -1)
```

---

### 2️⃣ Image Preprocessing Pipeline

```python
batch = np.random.randint(0, 256, size=(256, 128, 128, 3), dtype=np.uint8)
batch = batch / 255.0
batch = np.transpose(batch, (0, 3, 1, 2))
l2_norms = np.sqrt(np.sum(batch ** 2, axis=1))
```

---

### 3️⃣ Feature Engineering for ML

```python
f1 = np.sum(abs(X), axis=1)
f2 = np.max(X, axis=1)
f3 = np.min(X, axis=1)
features = np.vstack([f1, f2, f3]).T
```

---

### 4️⃣ Simulated Dense Layer + ReLU

```python
out = X @ W + b
relu_out = np.maximum(0, out)
```

---

## 🌟 Learnings:

* Mastered advanced NumPy operations
* Learned vectorization & broadcasting
* Preprocessing for ML pipelines
* Neural network layer simulation
* Built reusable image processing pipeline

---

## 🚶‍♂️‍➡️ Next Steps:

* Pandas Mastery
* Full ML Projects (Titanic, House Prices, CIFAR10)
* DL Frameworks: PyTorch, TensorFlow

---

**⭐️ Star this repo if you found it useful!**
**🚀 Follow my journey on LinkedIn: \[https://www.linkedin.com/in/jay-gopal-56b875215/]**
**#Python #NumPy #MachineLearning #AI**

---


