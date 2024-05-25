# Customer Segmentation

This project performs customer segmentation using the K-Means clustering algorithm. It uses a dataset containing customer information, such as age, annual income, and spending score, to group customers into distinct clusters.

## Dataset

The dataset should be in CSV format and contain the following columns:
- `CustomerID`: A unique identifier for each customer.
- `Gender`: The gender of the customer.
- `Age`: The age of the customer.
- `Annual Income (k$)`: The annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: A score assigned to the customer based on their spending habits, with 1 being the lowest and 100 being the highest.

## Project Structure

customer_segmentation/
│
├── data/       # Your input CSV file
│ 
├── results/    # Output CSV file with cluster labels
│ 
│
├── main.py     # Main script for customer segmentation
│  
├── README.md   # Project README file
|
└── requirements.txt # Python dependencies