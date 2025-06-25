# E-commerce Sales Forecasting and Customer Segmentation

## Project Overview
Ye project do parts me divided hai:

1. **Sales Forecasting**  
   - Daily sales data ka analysis aur forecasting ki gayi hai using ARIMA model.  
   - Agle 30 din ke liye sales forecast kiya gaya hai.  

2. **Customer Segmentation**  
   - Customer data ka use karke unhe alag-alag segments me classify kiya gaya hai using K-Means clustering.  
   - Segmentation se business ko targeted marketing me madad milegi.

## Data Description
- `data/sales_data.csv` — Daily sales data (Date, Sales)  
- `data/customer_data.csv` — Customer transaction data (AmountSpent, Frequency, Recency)

## Tools and Libraries Used
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn (KMeans)  
- Statsmodels (ARIMA)  
- Jupyter Notebook  

## How to Run the Project
1. Clone or download the repository.  
2. Make sure Python and required libraries are installed:  

pip install pandas matplotlib seaborn scikit-learn statsmodels jupyter

mathematica
Copy
Edit
3. Open Jupyter Notebook:  
jupyter notebook

markdown
Copy
Edit
4. Open and run the notebooks inside the `notebooks/` folder:  
- `sales_forecasting.ipynb`  
- `customer_segmentation.ipynb`  

## Results
- Sales forecast plot saved at `plots/sales_forecast.png`  
- Customer segmentation clusters plot saved at `plots/customer_segmentation.png`  

## Future Work
- Advanced forecasting models like Prophet or LSTM try karna  
- Web application banana for interactive visualization  
- Additional customer features use karke segmentation improve karna  

## Author
Yash Prajapati  
Email: yashprajapati.ds@gmail.com  
GitHub: https://github.com/Pr05-yash  
LinkedIn: https://www.linkedin.com/in/prajapati-yash-0451aa286/