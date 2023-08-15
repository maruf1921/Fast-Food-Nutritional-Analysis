# Fast Food Nutritional Analysis

This repository contains a comprehensive analysis of fast food items and their nutritional profiles across various restaurants in the USA. The analysis encompasses data cleaning, comparison of nutritional compositions, ranking of restaurants based on nutritional values, identification of healthier options, and visualization of nutritional distributions and trends.

## Dataset

The dataset used for this analysis is sourced from a CSV file (`fastfood.csv`) containing nutritional information for a variety of fast food items from different restaurants. The dataset includes attributes such as calories, total fat, protein, vitamins, and more.

## Analysis Steps

### Data Cleaning

1. **Renaming Columns**: The "Unnamed" column was renamed to a more meaningful name.

2. **Handling Missing Values**: Missing values in columns 'vit_a', 'vit_c', and 'calcium' were addressed by replacing them with appropriate values (e.g., mean or 0).

3. **Handling Zero Values**: Zero values in the 'trans_fat' column were replaced with the mean of non-zero values. Zero values in other specified columns were replaced with their respective means.

### Nutritional Composition Comparison

- The nutritional composition of different restaurants was compared for attributes such as calories, total fat, protein, vitamins A and C, and calcium. The comparison was visualized using bar plots.

### Restaurant Comparison

- Restaurants were ranked based on their average nutritional values, and a bar plot was created to visualize the ranking.

### Healthier Options Identification

- Criteria for defining healthier fast food items were established, such as low calories, low total fat, and high protein. Items meeting these criteria were filtered and displayed.

### Visualizations

Various types of visualizations were created to depict the distribution of nutritional values and identify trends:

- Histogram: Distribution of calories.
- Scatter Plot: Relationship between total fat and protein.
- Bar Chart: Average calories by restaurant.
- Box Plot: Protein content by restaurant.

## Files

- `fastfood.csv`: The original dataset with nutritional information for fast food items.
- `fastfood_cleaned.csv`: The cleaned dataset with missing and zero values replaced.
- `fastfoof.ipynb`: Jupyter Notebook containing the detailed analysis, data cleaning, visualizations, and comparisons.
- `fastfood.html`: This HTML file providing a visualization of the analysis.
- `README.md`: This README file providing an overview of the analysis.

## Usage

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/fast-food-nutritional-analysis.git
   ```

2. Navigate to the repository directory:

   ```
   cd fast-food-nutritional-analysis
   ```

3. Open and run the Jupyter Notebook `fastfood.ipynb` to explore the detailed analysis and visualizations.

## Acknowledgments

The analysis and code provided in this repository were created for educational purposes and as an example of conducting nutritional analysis using Python and data visualization libraries. The dataset used is for demonstration purposes and may not reflect actual nutritional information.
