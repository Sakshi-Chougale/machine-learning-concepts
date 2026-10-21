# K-Means Clustering

K-Means is an unsupervised Machine Learning algorithm that groups similar data points into clusters based on their features.

## Key Concepts

- **Clustering:** Grouping similar data points.
- **Centroids:** The center points of clusters.
- **WCSS:** Measures the sum of squared distances between data points and their assigned cluster centroids.
- **Elbow Method:** Helps estimate a suitable number of clusters.

## Implementation

This notebook uses the **Mall Customers dataset** to segment customers based on their annual income and spending score.

- Load and explore the dataset.
- Check missing values and remove unnecessary columns.
- Visualize annual income and spending score distributions.
- Apply the Elbow Method to select the number of clusters.
- Perform K-Means clustering with 5 clusters.
- Visualize customer segments and display cluster-wise customer counts.

## Real-World Applications

- Customer segmentation
- Market research
- Customer behavior analysis
- Grouping products by similar characteristics

## Tools & Technologies

Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

## How to Run

1. Install the required Python libraries.
2. Place `Mall_Customers.csv` in the appropriate location.
3. Update the dataset path in the notebook if required.
4. Run the notebook cells in order.

