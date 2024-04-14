# etlproject
I combined data from multiple sources to fill a SQLite database with employeee, inventory, and transaction data for a fictional coffee chain
## Database schema: 
  Employees: table populated from MySQL employee test database (modified)
  Locations: table populated from MySQL employee test database departments table (converted to represent locations instead)
  Pastry Inventory: table populated from CSV of pastry inventory (downloaded with Kaggle API)
  Products: table populated from CSV of products (downloaded with Kaggle API)
  Receipts: table populated from CSV of receipts (downloaded with Kaggle API)

## Data Sources:
  ### Employees MySQL test database (Employees, Locations)
  downloaded from https://github.com/datacharmer/test_db.git
  recreated on SQL server with modifications to fit coffee shop application

  ### Kaggle API 
  used the Kaggle API to download https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113 as CSV files

  ### CSV files from coffee shop sample data (Pastry Inventory, Products, Receipts)
  inserted those downloaded CSV files into the SQLite database 
