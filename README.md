
# Client Transaction Analysis Project

## Project Overview
This project involves analyzing a dataset of client transactions to uncover insights into sales trends, customer activity, and financial metrics. The analysis helps in identifying key categories and subcategories based on entry volumes, and computes detailed financial summaries for top clients, contributing to targeted strategic decisions.

## Data Exploration
- **Column Overview**: Initial exploration involves viewing the dataset's column names to understand the data structure.
- **Statistical Summary**: Utilization of the `describe()` function to get a summary of the numerical attributes.
- **Category Analysis**: Identification of the top item categories and subcategories to pinpoint areas with high sales volume.

## Data Transformation
- **Subtotal Calculation**: Each transaction line's subtotal is calculated based on unit prices and quantities.
- **Shipping Cost Computation**: A shipping cost column is created, where costs vary based on item weight.
- **Total Price Calculation**: A total price column that includes subtotal, shipping cost, and a 9.25% sales tax.
- **Cost and Profit Analysis**: Calculation of the cost per line and the profit per line, providing insights into profitability.

## Results Confirmation
- **Order Verification**: Specific orders are checked against provided totals to confirm accuracy of the data transformations and calculations.

## Data Summarization and Analysis
- **Client Summary**: Creation of a summary DataFrame showing total units purchased, shipping prices, total revenue, and profits for the top clients, sorted by total profit.
- **Formatting for Presentation**: Formatting financial figures into millions of dollars for clarity and professional presentation.

## Conclusion
The project yields critical insights into the business's operational effectiveness and client profitability. It supports strategic decision-making by highlighting profitable sectors and optimizing client management strategies.

## How to Use
- Ensure all data files are correctly placed in the `Resources` directory.
- Run the Jupyter Notebook to reproduce the analysis and modify parameters as needed to focus on different aspects of the data.

