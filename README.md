# Customer Journey Data Model Project
## Overview

This project aims to analyze and visualize the customer journey using a comprehensive data model. The focus is on understanding customer behavior across various product holdings, ensuring data quality and regulatory compliance, and providing actionable insights for business decision-making. The project uses an e-commerce dataset to track and analyze the customer journey, with detailed steps for data preprocessing, analysis, and visualization.

## Project Structure
~~~
Customer-Journey-Data-Model/
├── data/
│   └── online_retail.csv
├── notebooks/
│   └── Customer_Journey_Data_Model.ipynb
├── images/
│   └── Frequency_Distribution.png
│   └── Monetary_Distribution.png
│   └── Recency_Distribution.png
│   └── RFM_Segmentation.png
└── README.md
~~~
- **data/**: Contains the dataset used for the project.
- **notebooks/**: Contains the Jupyter notebook with the detailed project implementation.
- **images/**: Contains images generated from the project for visualization.
- **README.md**: This file.
- **requirements.txt**: List of required Python packages.

## Dataset

The dataset used for this project is the "Online Retail" dataset, which can be found on Kaggle:
- "https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset"

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Customer-Journey-Data-Model.git
   cd Customer-Journey-Data-Model
   ```

2. **Create a virtual environment and activate it:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Download the dataset:**
   Place the `online_retail.csv` file in the `data/` directory.

2. **Run the Jupyter notebook:**
   ```bash
   jupyter notebook notebooks/Customer_Journey_Data_Model.ipynb
   ```

3. **Follow the steps in the notebook:**
   The notebook contains detailed steps for data loading, preprocessing, customer journey mapping, data quality checks, and visualization.

## Project Steps

### 1. Load and Explore the Data

Load the dataset and perform an initial exploration to understand its structure and content.

### 2. Data Preprocessing

Handle missing values, convert columns to appropriate data types, and clean the data to ensure integrity.

### 3. Customer Journey Mapping

Aggregate data by customer and track their interactions over time, calculating key metrics like total spent and transaction counts.

### 4. Data Quality and Compliance

Ensure data quality and regulatory compliance by checking for and removing invalid data.

### 5. Insights and Analysis

Analyze customer behavior, purchase patterns, and segment customers using RFM (Recency, Frequency, Monetary) analysis.

### 6. Visualization

Create visualizations to present the insights derived from the data, including histograms and scatter plots for RFM segmentation.

### 7. Conclusion

Summarize the findings and discuss business implications based on the analysis.

## Visualizations

### Recency Distribution
![Recency Distribution](images/Recency_Distribution.png)

### Frequency Distribution
![Frequency Distribution](images/Frequency_Distribution.png)

### Monetary Distribution
![Monetary Distribution](images/Monetary_Distribution.png)

### RFM Segmentation
![RFM Segmentation](images/RFM_Segmentation.png)

## Conclusion

This project provides a comprehensive approach to analyzing the customer journey, offering valuable insights for improving customer engagement and business performance. By leveraging these techniques, businesses can make data-driven decisions to enhance their customer relationship management strategies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Kaggle for providing the dataset.
- Aston University for the support and resources during the M.Sc in Data Analytics program.

## Contact

For any questions or inquiries, please contact:
- Dev Krishna Vijayaradhan
- Email: devkrishnavijayaradhan@gmail.com
- LinkedIn: "https://www.linkedin.com/in/devkrishnav/"

---

Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!
```
