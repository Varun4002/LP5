# LP5

Coursework repository covering **Deep Learning** and **High Performance Computing** practical assignments.

## Contents

- [Deep Learning (Lp5_DL)](#deep-learning-lp5_dl)
- [High Performance Computing (Lp5_HPC)](#high-performance-computing-lp5_hpc)

---

## Deep Learning (Lp5_DL)

Python-based projects using TensorFlow/Keras, PyTorch, and Scikit-learn.

| Project | Description | Technique |
|---------|-------------|-----------|
| **P5_BOSTON** | Boston housing price prediction | Neural Network (Keras) |
| **P6_A_OCR** | Handwritten digit recognition | MNIST, Dense Neural Network |
| **P6_B_IMDB** | Movie review sentiment analysis | NLP with IMDB dataset |
| **P7_B_FASHION** | Clothing item classification | CNN with Fashion-MNIST |
| **P8_GOOGLE_STOCK_PRICE** | Stock price prediction | LSTM (PyTorch) |

### Requirements

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras torch
```

### Running

```bash
cd Lp5_DL
jupyter notebook
# Or run individual scripts
python P5_BOSTON/5BostonLR.py
```

---

## High Performance Computing (Lp5_HPC)

C/C++ projects demonstrating parallel computing with OpenMP and CUDA.

| Project | Description | Technique |
|---------|-------------|-----------|
| **P1** | Parallel BFS and DFS graph traversal | OpenMP |
| **P2** | Parallel Bubble Sort and Merge Sort | OpenMP |
| **P3** | Parallel Min/Max/Sum/Average | OpenMP reduction |
| **P4_OMP** | Matrix multiplication and addition | OpenMP |
| **P4_CUDA** | Matrix multiplication and addition | CUDA GPU |

### OpenMP

```bash
cd Lp5_HPC
g++ -fopenmp P1_Parallel_BFS_DFS.cpp -o p1
./p1
```

### CUDA

```bash
cd Lp5_HPC/P4_CUDA
nvcc P4_matrix_multiplication_Cuda.c -o matmul
./matmul
```

---

## Structure

```
LP5/
├── Lp5_DL/          # Deep Learning projects
│   ├── P5_BOSTON/
│   ├── P6_A_OCR/
│   ├── P6_B_IMDB/
│   ├── P7_B_FASHION/
│   └── P8_GOOGLE_STOCK_PRICE/
└── Lp5_HPC/         # High Performance Computing projects
    ├── P1_Parallel_BFS_DFS.cpp
    ├── P2_Parallel_bubble_merge.cpp
    ├── P3_Parallel_MIN_MAX_SUM_AVG.cpp
    ├── P4_OMP/
    └── P4_CUDA/
```

---

## License

Academic coursework project.
