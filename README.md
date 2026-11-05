# Retail Customer Segmentation and Segment-Based Recommendations

A retail analytics project using transaction-level data to engineer customer features, identify behavioural segments with K-Means, and explore recommendations tailored to each segment.

**Academic context:** MSc in Business Intelligence & Analytics, ISCAP (2025/26)  
**Author:** João Coelho

## Project objective

The project aims to transform raw retail transactions into customer-level behavioural features and use unsupervised learning to identify groups with similar purchasing patterns.

## Methodology

1. **Data preparation:** clean and structure the transaction data.
2. **Customer-level feature engineering:** calculate behavioural indicators such as average purchase value, purchase frequency, and monthly trend.
3. **Customer segmentation:** apply K-Means to the engineered feature set.
4. **Segment interpretation:** profile the resulting clusters using their characteristic purchasing behaviour.
5. **Recommendations:** develop segment-based product recommendation logic.

## Technology stack

- Python, pandas, and NumPy
- SciPy
- scikit-learn (K-Means and preprocessing)
- Matplotlib and Seaborn
- Google Colab

## Data

The source file `Retalho.csv` is approximately 45 MB and is not included in the repository. Place the file in Google Drive and update the path in the notebook's first data-loading cell.

## Running the notebook

1. Open the notebook in Google Colab.
2. Upload `Retalho.csv` to Google Drive.
3. Update the dataset path in the configuration cell.
4. Run the notebook from data cleaning through clustering and segment analysis.

## Scope and limitations

- Cluster quality depends on feature selection, scaling, the number of clusters, and the random initialisation.
- Segment labels are interpretations of observed purchasing behaviour, not fixed customer traits.
- Recommendations are exploratory and should be evaluated with appropriate offline or controlled experiments before operational use.
- The dataset is not bundled with the repository; reproduction requires access to the original file.
