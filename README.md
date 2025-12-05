# UNSUPERVISED LEARNING PROJECT - DIMENSIONALITY REDUCTION & CLUSTERING

**Language:** Python  
**Environment:** Jupyter Notebook  
**README Language:** English

---

## ⭐ Project Summary
This project implements a complete **unsupervised learning pipeline**, following the structure of **AAMD – Assignment 2**.  
Two datasets are analyzed (`A2-real.txt` and `A2-synthetic.txt`) using a variety of dimensionality‑reduction and clustering techniques to uncover hidden structure and evaluate separability.

The notebook applies the following methods:
- **PCA** (Principal Component Analysis)  
- **t‑SNE**  
- **k‑means clustering**  
- **Agglomerative Hierarchical Clustering (AHC)**  
- **Autoencoder (unsupervised neural network)**  
- **Self‑Organizing Map (SOM)**  

The goal is to compare results across techniques, interpret clusters, and visually analyze the latent structure of the datasets.

---

## 🧩 Technologies & Skills Demonstrated

### **Unsupervised Learning Techniques**
- Linear dimensionality reduction (PCA)  
- Nonlinear embedding (t‑SNE)  
- Classical clustering (k‑means)  
- Hierarchical clustering (AHC, dendrograms)  
- Neural-based representation learning (Autoencoder)  
- Self-organizing neural maps (SOM)

### **Python & ML Libraries**
- `numpy`, `pandas`  
- `matplotlib`, `seaborn`  
- `sklearn` (PCA, k-means, AHC, t-SNE)  
- `torch` (autoencoder)  
- `minisom` (SOM)

### **Analysis Skills**
- Visualization & interpretation  
- Understanding cluster separability  
- Comparing latent spaces  
- Evaluating strengths and weaknesses of each method  

---

## 📁 Project Structure

```
AAMD-Unsupervised-Learning-Dimensionality-Reduction-Clustering/
│
├── A2.ipynb                            → Main notebook with full analysis
├── A2-real.txt                         → Real dataset
├── A2-synthetic.txt                    → Synthetic dataset
└── .ipynb_checkpoints/                 → System folder (ignored)
```

### Notebook Structure
1. Library imports  
2. Data loading  
3. Preprocessing  
4. PCA  
5. t-SNE  
6. k-means clustering  
7. Agglomerative Hierarchical Clustering (AHC)  
8. Autoencoder (encoding + reconstruction + 2D latent space)  
9. Self-Organizing Map (SOM)  
10. Final comparison & discussion  

---

## 🔍 Project Details

### **1. Data Preprocessing**
- Normalization / scaling  
- Inspection of distributions  
- Conversion to numerical matrices  

### **2. PCA**
- Reduces dimensionality to 2D  
- Captures most variance linearly  
- Visualizes projected scatterplots  

### **3. t‑SNE**
- Nonlinear manifold learning  
- Captures local neighborhood structure  
- Often yields well-separated clusters  

### **4. k‑means**
- Partitions data into *k* clusters  
- Evaluated visually via 2D projections  
- Sensitive to initialization and scaling  

### **5. AHC**
- Linkage methods (ward, complete…)  
- Dendrogram visualization  
- Better for hierarchical structure  

### **6. Autoencoder**
- Neural network that compresses data into a 2D latent space  
- Encoder → latent representation → decoder  
- Visualizes learned features and reconstructions  

### **7. SOM (Self‑Organizing Map)**
- Grid of neurons trained using competitive learning  
- Produces a 2D topology-preserving embedding  
- Useful for nonlinear structure discovery  

---

## ▶️ How to Run the Project

### **1. Install dependencies**
```
pip install numpy pandas matplotlib seaborn scikit-learn minisom torch
```

### **2. Launch Jupyter**
```
jupyter notebook
```

### **3. Open**
```
A2-Practica2-FormatCorrecte.ipynb
```

### **4. Ensure datasets exist**
Place:
- `A2-real.txt`  
- `A2-synthetic.txt`  
in the same folder as the notebook.

### **5. Run cells sequentially**
Evaluate each method and compare visualizations.

---

## ✔ Summary
This project provides a full exploration of **unsupervised learning** using both classical ML techniques and neural models.  
It demonstrates how different dimensionality‑reduction and clustering approaches can reveal structure in data, and how to compare these representations meaningfully.

