# Centroid Optimization of K-Means Using Ant Colony Optimization for Culinary MSME Clustering

https://github.com/user-attachments/assets/8f3ea1e1-88d8-4293-b5a7-a3b1ffce04b0

<img width="344" height="143" alt="ACO" src="https://github.com/user-attachments/assets/7ed94ff5-c3a8-46c6-94be-b3f7b8d617ee" />


## 📌 Description
This research focuses on improving the clustering performance of Culinary MSME (Micro, Small, and Medium Enterprises) data in the Special Region of Yogyakarta using a hybrid approach between the K-Means algorithm and Ant Colony Optimization (ACO).

K-Means is widely used for clustering because of its simplicity and efficiency. However, its performance highly depends on the initial centroid selection, which may lead to suboptimal clustering results. To overcome this limitation, Ant Colony Optimization is utilized to optimize centroid initialization before the K-Means clustering process.

The study evaluates clustering quality using the Silhouette Score and compares the performance between standard K-Means and ACO-optimized K-Means.

---

# 👨‍💻 Author
- Muhammad Fharahbi Fachri
- Lisna Zahrotun

Affiliation:
- Informatics Department, Ahmad Dahlan University, Yogyakarta, Indonesia

---

# 📖 Research Information
- Journal: Journal of Information Systems and Informatics
- Volume: 8
- Issue: 1
- Publication Date: February 2026
- DOI: 10.63158/journalisi.v8i1.1443

---

# 🎯 Research Objectives
This study aims to:
1. Apply K-Means clustering to Culinary MSME data.
2. Optimize centroid initialization using Ant Colony Optimization.
3. Compare clustering performance between standard K-Means and ACO-based K-Means.
4. Identify the optimal cluster configuration using Silhouette Score evaluation.

---

# 📂 Dataset
The dataset was obtained from the Yogyakarta City Office of Industry, Cooperatives, and MSMEs.

## Dataset Characteristics
- Total data: 1,336 Culinary MSMEs
- Region: Special Region of Yogyakarta
- Sector: Culinary MSMEs

## Features Used
- Annual Turnover
- Final Education
- Land/Building Ownership Status
- Insurance Ownership
- Electronic Media Facilities
- Government Assistance Capital
- Gender

---

# ⚙️ Methodology

## 1. Data Preprocessing
The preprocessing stage includes:
- Missing value checking
- Duplicate data checking
- Feature selection
- Data transformation

## 2. Data Transformation
Several encoding techniques were applied:
- Binary Encoding
- Label Encoding
- Manual Mapping

## 3. Clustering Using K-Means
K-Means clustering was performed with:
- K = 2
- K = 3
- K = 4

Euclidean Distance Formula:

```math
d(x,y)=\sqrt{\sum_{i=1}^{n}(x_i-y_i)^2}
```

## 4. Centroid Optimization Using ACO
ACO was used to optimize centroid initialization using pheromone-based probabilistic searching.

Probability Formula:

```math
P_{ij}=\frac{\tau_{ij}^{\alpha}\times\eta_{ij}^{\beta}}{\sum_k \tau_{ik}^{\alpha}\times\eta_{ik}^{\beta}}
```

Pheromone Update Formula:

```math
\tau_{ij}=(1-\rho)\tau_{ij}+\Delta\tau_{ij}
```

## 5. Evaluation
Clustering quality was evaluated using Silhouette Score.

Silhouette Score Formula:

```math
S(i)=\frac{b_i-a_i}{\max(a_i,b_i)}
```

---

# 📊 Results

## K-Means Results

| Cluster | Silhouette Score |
|---|---|
| 2 | 0.88 |
| 3 | 0.81 |
| 4 | 0.81 |

## ACO-KMeans Results

| Cluster | Silhouette Score |
|---|---|
| 2 | 0.89 |
| 3 | 0.86 |
| 4 | 0.92 |

## Best Result
- Best Cluster: K = 4
- Best Silhouette Score: 0.92

The results show that Ant Colony Optimization successfully improves clustering performance and cluster stability.

---

# 📈 Cluster Characteristics

## Cluster 1
- High income MSMEs
- Strong digital adoption
- Dominated by S1 education
- Suitable for advanced digital marketing programs

## Cluster 2
- Low-middle income MSMEs
- WhatsApp-dominated communication
- Requires digital literacy support

## Cluster 3
- Middle income MSMEs
- Active e-commerce usage
- Potential for marketplace integration

## Cluster 4
- Very low income MSMEs
- Low technology adoption
- High dependency on government assistance

---

# 🚀 Technologies & Libraries
- Python
- NumPy
- Pandas
- Scikit-Learn
- SciPy

---

# 🧠 Algorithms Used
- K-Means Clustering
- Ant Colony Optimization (ACO)

---

# ⚠️ Limitations
- Only uses Culinary MSME data from Yogyakarta.
- Evaluation only uses Silhouette Score.
- ACO increases computational time significantly (approximately 20–40 minutes per cluster).

---

# 🔮 Future Work
Future research may include:
- Particle Swarm Optimization (PSO)
- Genetic Algorithm (GA)
- Firefly Algorithm
- Real-time clustering systems
- Larger MSME datasets from different regions

---

# 📚 Citation

```bibtex
@article{fachri2026aco,
  title={Centroid Optimization of K-Means Using Ant Colony Optimization for Culinary MSME Clustering},
  author={Fachri, Muhammad Fharahbi and Zahrotun, Lisna},
  journal={Journal of Information Systems and Informatics},
  volume={8},
  number={1},
  pages={860--888},
  year={2026},
  doi={10.63158/journalisi.v8i1.1443}
}
```

---

# 📄 License
This article is distributed under the CC-BY License.
