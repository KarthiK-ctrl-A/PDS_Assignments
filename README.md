# PDS Assignment 1

This repository contains solutions for two questions from the PDS Assignment 1.

- Name : Sai Karthik Patri
- Student ID: 16361167
- StudentMail : sphtb@umsystem.edu

---

## Question 1 - Frailty Prediction Workflow

The answer for **Question 1** is provided in the Jupyter Notebook file named `Question_1.ipynb`.

### Folder Structure:
├── Question_1.ipynb # Jupyter notebook for Question 1 solution



### Description:
- The `Question_1.ipynb` notebook contains the complete workflow for the frailty prediction problem.
- It covers the three stages of the reproducible workflow: 
  1. **Data Acquisition & Cleaning**: Gathering data and cleaning it for processing.
  2. **Data Processing**: Applying data transformations to enable model building.
  3. **Modeling & Prediction**: Building and evaluating the frailty prediction model.
- The folder structure and stages are explained in detail in the notebook, with steps to reproduce the workflow and how to organize files.

---

## Question 2 - Student Performance Visualization

The answer for **Question 2** is available in the `student_performance` directory. It consists of five different data visualizations, along with analysis based on the given student performance dataset.

### Folder Structure:

```
student_performance/
├── data/
│   └── StudentsPerformance.csv            # Raw dataset containing student performance information
├── scripts/
│   └── main.ipynb                         # Jupyter notebook with data visualization code
├── analysis/
│   ├── visualizations/                    # Folder containing images of the visualizations
│   │   ├── bar_gender.png                 # Bar plot for gender distribution
│   │   ├── box_math_scores.png            # Box plot for math scores vs parental level of education
│   │   ├── scatter_math_reading.png       # Scatter plot for math vs reading scores
│   │   ├── heatmap_correlation.png        # Heatmap for correlation matrix
│   │   └── pie_lunch_type.png             # Pie chart for lunch type distribution
```

### Description:
- **Dataset**: The dataset for student performance is located in `data/StudentsPerformance.csv`.
- **Jupyter Notebook**: The code for visualizations is provided in `scripts/main.ipynb`. It generates five different data visualizations from the dataset.
- **Visualizations**: All generated visualizations are saved as `.png` files in the `analysis/visualizations` folder.

### Visualizations Explained:
1. **Bar Plot for Gender Distribution** (`bar_gender.png`): 
   - Visualizes the distribution of male and female students.
   - Analysis: It helps to understand the gender composition in the dataset.
  
2. **Box Plot for Math Scores vs Parental Education Level** (`box_math_scores.png`):
   - Displays the distribution of math scores based on parental education level.
   - Analysis: Highlights how parental education may affect student math performance.
  
3. **Scatter Plot for Math vs Reading Scores** (`scatter_math_reading.png`):
   - Plots the relationship between math and reading scores.
   - Analysis: Reveals correlations or trends between student performance in math and reading.
  
4. **Heatmap of Correlation Matrix** (`heatmap_correlation.png`):
   - Shows the correlation between numeric variables such as math, reading, and writing scores.
   - Analysis: Easily identifies strong positive or negative correlations between scores.
  
5. **Pie Chart for Lunch Type Distribution** (`pie_lunch_type.png`):
   - Visualizes the proportion of students receiving free/reduced lunch versus standard lunch.
   - Analysis: Helps in understanding how lunch type is distributed across the dataset.

---

### Execution:

1. **Question 1**:
   - Open `Question_1.ipynb` in Jupyter Notebook.
   - Run the notebook to reproduce the frailty prediction workflow.

2. **Question 2**:
   - Navigate to the `student_performance/` directory.
   - Open `main.ipynb` in Jupyter Notebook and run the cells to generate the visualizations.
   - All visualizations will be saved automatically in the `analysis/visualizations/` folder.
