# K-Means Clustering – Customer Segmentation  

## Objective  
Perform **unsupervised learning** using the **K-Means** algorithm to segment customers into distinct groups based on spending behavior and income.  

## Tools & Libraries  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  


## Dataset  
**Mall Customers Dataset** – Contains details about customers including:  
- Customer ID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)  

## Steps Followed  

### **1. Data Loading & Exploration**  
- Loaded dataset using Pandas  
- Checked missing values & data types  
- Performed exploratory visualizations  

### **2. Feature Selection & Scaling**  
- Selected relevant features (`Annual Income (k$)` & `Spending Score (1-100)`)  
- Standardized features using `StandardScaler`  

### **3. Finding Optimal K (Elbow Method)**  
- Computed inertia for K = 1 to 10  
- Plotted **Inertia vs K** curve to find the elbow point  

### **4. Model Training**  
- Applied **K-Means** with optimal K  
- Assigned cluster labels to customers  

### **5. Cluster Evaluation**  
- Measured **Silhouette Score** to evaluate cohesion & separation of clusters  

### **6. Visualization**  
- Scatter plots with color-coded clusters  
- Centroid plotting for clarity  


## Results  
- Optimal K found using **Elbow Method**  
- **Silhouette Score** indicates good cluster separation  
- Visualizations clearly show distinct customer segments  


## What You’ll Learn  
- Basics of **unsupervised learning**  
- Understanding **K-Means clustering**  
- Choosing optimal K using **Elbow Method**  
- Evaluating clusters with **Silhouette Score**  
- Visualizing high-dimensional data in 2D  




## Sample Output Graphs  

### Elbow Method   

### Cluster Visualization  


## File Structure 
Task8.ipynb 
Mall_Customers.csv
ElbowMethod.png
K-meansClusters.png
README.md
