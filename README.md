### Medical Data Visualizer

###### Technologies:
<p align="center">
<img src="https://img.icons8.com/color/75/000000/python.png" width="75" height="75" alt="Python" style="margin: 10px 15px 0 15px;" />
<img src="https://pandas.pydata.org/static/img/pandas_white.svg" width="175" height="75" alt="Pandas" style="margin: 10px 15px 0 15px;" />
<img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" width="75" height="75" alt="Seaborn" style="margin: 10px 15px 0 15px;" />
<img src="https://matplotlib.org/stable/_static/logo2_compressed.svg" width="75" height="75" alt="Matplotlib" style="margin: 10px 15px 0 15px;" />
</p>

### Try it!

To run the Medical Data Visualizer application, follow the instructions in the Setup section below.

## Project Structure

- `medical_data_visualizer.py`: Contains the implementation of the medical data visualization and analysis functions.
- `main.py`: Used for development and testing the functions.
- `test_module.py`: Contains unit tests for validating the implementation.

## Setup

### Prerequisites

- Python 3 installed
- Pandas installed
- Seaborn installed
- Matplotlib installed

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/creinis/medical-dv-fcc-data-analyses-py-cert.git
   cd medical-data-visualizer
   ```

2. Install the required libraries:
   ```bash
   pip install pandas seaborn matplotlib
   ```

3. Run the Medical Data Visualizer script:
   ```bash
   python3 main.py
   ```

## Medical Data Visualizer

### Functionality

The Medical Data Visualizer analyzes and visualizes medical examination data to explore the relationship between cardiac disease, body measurements, blood markers, and lifestyle choices. The dataset includes various measurements and test results collected during medical examinations.

### Functions

#### draw_cat_plot Function

This function creates a categorical plot showing the counts of good and bad outcomes for the cholesterol, gluc, alco, active, and smoke variables for patients with and without cardiovascular disease.

#### draw_heat_map Function

This function creates a heatmap displaying the correlation matrix of the medical examination features after cleaning the data.

### Practical Use Case

This visualizer is useful for healthcare professionals and researchers to analyze medical data, identify correlations, and gain insights into factors associated with cardiovascular disease.

### Benefits

- **Data Visualization:** Provides clear and informative visual representations of medical data.
- **Efficient Data Analysis:** Utilizes Pandas and Seaborn for efficient data manipulation and visualization.
- **Insightful Correlations:** Helps in identifying relationships between various medical metrics and lifestyle factors.

## How to Use

1. Call the `draw_cat_plot` function to generate the categorical plot.
2. Call the `draw_heat_map` function to generate the heatmap.

### Example Usage

```python
import medical_data_visualizer

# Generate and save the categorical plot
cat_plot_fig = medical_data_visualizer.draw_cat_plot()

# Generate and save the heatmap
heat_map_fig = medical_data_visualizer.draw_heat_map()
```

### Example Output

**Categorical Plot:**

![Categorical Plot](https://github.com/creinis/medical-dv-fcc-data-analyses-py-cert/blob/11e9b9c7186599d424e9e0069fdcecf00f4fbe0d/catplot.png)

**Heat Map:**

![Heat Map](https://github.com/creinis/medical-dv-fcc-data-analyses-py-cert/blob/11e9b9c7186599d424e9e0069fdcecf00f4fbe0d/heatmap.png)

### Additional Information

- **Dataset:** Contains medical examination data with various measurements and test results.
- **Comprehensive Analysis:** Visualizes correlations and distributions of key medical metrics and lifestyle factors.

---
#### This is a FreeCodeCamp Challenge for Data Analysis with Python Projects Certification.
<p align="center">
<img src="https://cdn.freecodecamp.org/platform/universal/fcc_primary.svg" width="250" height="75" alt="freeCodeCamp" style="margin: 0 15px; opacity: 0.6" />
</p>