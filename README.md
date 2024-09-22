

# DonorsChoose TSNE Analysis

This project applies **t-Distributed Stochastic Neighbor Embedding (t-SNE)** to the DonorsChoose dataset to visualize high-dimensional data and uncover patterns in project approvals.

## Dataset
- **Dataset**: DonorsChoose.org project proposals.
- **Features**: Project titles, essays, categories, and metadata about teachers and schools.
- **Target**: Predict project approval.

## Key Steps
1. **Data Preprocessing**:
   - Handled text features like project essays, titles, and categorical data.
   - Applied TF-IDF vectorization and sentiment analysis.

2. **Dimensionality Reduction**:
   - Utilized t-SNE to visualize high-dimensional data in 2D space.
   - Compared project clusters based on approval status.

3. **Analysis**:
   - Examined the influence of features like teacher experience, project cost, and textual information on clustering patterns.
   - Visualized clusters to assess patterns of approval.

## Conclusion
t-SNE provided meaningful visualizations that helped highlight the differences in project approval patterns based on textual and categorical data. Clustering allowed insights into project proposals most likely to be approved.

