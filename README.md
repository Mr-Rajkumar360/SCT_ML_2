## Project Title: **Mall Customer Segmentation using K-means Clustering**

### Project Overview
This project aims to segment customers of a retail store into distinct groups based on their purchasing behavior. The K-means clustering algorithm is employed to achieve this, allowing the retail store to target its customers more effectively by understanding their spending patterns.

### Dataset
- **Dataset Name**: Mall Customer Dataset
- **Dataset Description**: The dataset consists of customer information such as Customer ID, Gender, Age, Annual Income (in $), and Spending Score (a value between 1 and 100). For clustering, only Annual Income and Spending Score are considered.
- **Source**: The dataset can be found [https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python](#).

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/GundlapalliRajkumar/SCT_ML_2.git
   ```
2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```
### Code Overview
- **Data Preprocessing**: The data is preprocessed by dropping non-essential columns like CustomerID, Gender, and Age.
- **Data Visualization**: Scatter plots are created to visualize the relationship between Annual Income and Spending Score.
- **K-means Clustering**: The elbow method is used to determine the optimal number of clusters. The dataset is then segmented into clusters using the K-means algorithm.
- **Cluster Visualization**: The final clusters and their centers are visualized using scatter plots.

### Visualization
*The image shows the segmentation of customers into five clusters based on their Annual Income and Spending Score. Each color represents a different cluster, and the red points mark the cluster centers.*
![K-means Clustering of Mall Customers](https://github.com/user-attachments/assets/0cdafb6f-d449-46e6-8c92-37cc9d229805) 
### Usage
To run the project, execute the following command in your terminal:
```bash
python Customer.py
```

### Results
The project successfully segments Mall customers into distinct groups, which can be used for targeted marketing strategies by the retail store.
