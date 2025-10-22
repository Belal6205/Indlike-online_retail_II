

## Notebook Overview: Online Retail Data Analysis

### 1. **Initial Setup**
- Importing necessary libraries: pandas, numpy, seaborn, matplotlib, scikit-learn
- Uploading the dataset `online_retail_combined.csv` using Google Colab

### 2. **Data Loading & Initial Exploration**
- Loading the dataset and displaying first 6 rows
- The dataset contains columns: Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, Country

### 3. **Data Preprocessing**
- Renaming 'Price' column to 'UnitPrice'
- Converting data types: InvoiceDate to datetime, Quantity and UnitPrice to numeric
- Removing rows with missing dates, quantities, or prices
- Creating 'TotalSales' column (Quantity × UnitPrice)

### 4. **Feature Engineering**
- Creating 'YearMonth' column from InvoiceDate
- Calculating monthly sales totals

### 5. **Data Visualization**
- Plotting monthly sales trends (though the plot itself isn't visible in the code shown)

### Key Features of the Dataset:
- Transaction-level retail data
- International sales (multiple countries)
- Customer purchase history
- Product information with descriptions
- Sales amounts and quantities

The notebook appears to be set up for customer segmentation analysis using clustering algorithms (KMeans is imported), suggesting the analysis will likely explore:
- Customer purchasing patterns
- Sales trends over time
- Product performance
- Customer segmentation based on purchasing behavior

Would you like me to help you with any specific aspect of this analysis or explain any particular part of the code in more detail?
