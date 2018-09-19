# Dimensionality Reduction

![inversion](http://phdthesis-bioinformatics-maxplanckinstitute-molecularplantphys.matthias-scholz.de/fig_pca_illu3d.png)

### What's the problem?
The problem is the **Curse of dimensionality**:
*The curse of dimensionality refers to various phenomena that arise when analyzing and organizing data in high-dimensional spaces (often with hundreds or thousands of dimensions) that do not occur in low-dimensional settings such as the three-dimensional physical space of everyday experience.*

Indeed, as you have seen till now, a lot of machine learning problems involve thousands or millions of features and this make training very slow and also the result not too accurate.

### What we do then?
We reduce these dimensions! It's like when you compress your files to save space. Of course with this operation we lose some information, but in theory those information are "useless" for our goal.

### Techniques:
- PCA (projection)
- Kernel PCA
- LLE (different approach --> manifold learning)
- MDS
- t-SNE (very good when you want to **visualize** your data)
- ...

In this jupyter notebook I explore PCA and t-SNE using MNIST dataset.

### Reference
- [Wikipedia](https://en.wikipedia.org/wiki/Dimensionality_reduction)
- [Hacker Noon article](https://hackernoon.com/supervised-machine-learning-dimensional-reduction-and-principal-component-analysis-614dec1f6b4c)