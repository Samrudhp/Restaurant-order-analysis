# Restaurant-order-analysis
# Restaurant Order Analysis 🍽️

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)


## Description
A data analysis project that explores restaurant order patterns, popular dishes, and sales performance using Python and Jupyter Notebook. This analysis helps restaurant owners and managers make data-driven decisions by visualizing ordering trends and identifying top-performing menu items.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Data Requirements](#data-requirements)
- [Analysis Components](#analysis-components)
- [Visualizations](#visualizations)
- [Contributing](#contributing)


## Installation

### Clone the Repository
```bash
git clone https://github.com/Samrudhp/Restaurant-order-analysis.git
cd Restaurant-order-analysis
```

### Set Up Environment
```bash
# Create and activate virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt
```

### Required Libraries
```txt
pandas
numpy
matplotlib
jupyter
```

## Usage

1. **Prepare Your Data**
   - Place your CSV files in the project directory:
     - `order_details.csv`
     - `menu_items.csv`

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

3. **Open and Run Analysis**
   - Navigate to `restaurant_analysis.ipynb`
   - Run cells sequentially to perform analysis

## Data Requirements

### order_details.csv
```
Required columns:
- item_id: Unique identifier for menu items
- order_time: Timestamp of orders
```

### menu_items.csv
```
Required columns:
- menu_item_id: Unique identifier matching item_id
- item_name: Name of the dish
- price: Price of the item
```

## Analysis Components

### 1. Data Loading and Preparation
- Loads order details and menu items from CSV files
- Merges datasets based on item IDs
- Performs initial data exploration

### 2. Popular Dishes Analysis
- Calculates and visualizes top 10 most ordered dishes
- Creates bar chart showing order frequencies

### 3. Sales Performance Analysis
- Calculates total sales amount per dish
- Visualizes top 10 dishes by revenue

### 4. Time-based Order Pattern Analysis
- Analyzes order distribution across hours
- Identifies peak ordering times

## Visualizations

The notebook generates three key visualizations:
1. **Top 10 Most Ordered Dishes**
   - Bar chart showing order frequency
   - Helps identify customer favorites

2. **Top 10 Dishes by Sales Amount**
   - Bar chart showing revenue generation
   - Identifies most profitable items

3. **Hourly Order Distribution**
   - Line graph showing order patterns
   - Helps optimize staffing and preparation

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact

Samrudh P - [@GitHub](https://github.com/Samrudhp)

Project Link: [https://github.com/Samrudhp/Restaurant-order-analysis](https://github.com/Samrudhp/Restaurant-order-analysis)

## Acknowledgments

* Data analysis techniques inspired by real-world restaurant operations
* Visualization best practices from the Python data science community
* Special thanks to pandas and matplotlib development teams
 
