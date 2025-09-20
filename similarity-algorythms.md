
```
Vector Similarity Algorithms (for Embeddings)
│
├── Angular / Direction-Based
│   └── Cosine Similarity
│       - Measures angle between vectors
│       - Scale-invariant
│
├── Distance-Based
│   ├── Euclidean Distance (L2)
│   │   - Straight-line distance
│   │   - Sensitive to magnitude
│   ├── Manhattan Distance (L1)
│   │   - Sum of absolute differences
│   │   - Robust to outliers
│   └── Minkowski Distance
│       - Generalized Lp norm
│
├── Correlation-Based
│   └── Pearson Correlation
│       - Linear dependency
│       - Similar to cosine, but mean-centered
│
├── Probabilistic / Distribution-Based
│   ├── KL Divergence
│   ├── Jensen–Shannon Divergence
│   └── Hellinger Distance
│       - Useful if embeddings represent distributions
│
├── Set / Overlap Measures (for sparse/binary embeddings)
│   ├── Jaccard Similarity
│   ├── Dice Coefficient
│   └── Overlap Coefficient
│
└── Learned / Task-Specific Similarities
    ├── Dot Product (raw similarity, used in many models)
    ├── Mahalanobis Distance (covariance-aware)
    ├── Siamese / Triplet Loss embeddings
    └── Contrastive Learning (SimCLR, CLIP, etc.)
```