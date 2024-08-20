# Sleep_Quality_Prediction


# Overview
This project analyzes a dataset containing various attributes related to sleep quality, physical activity, and other health-related metrics. The dataset consists of 374 records, each with 13 attributes, including demographic data, health metrics, and sleep-related characteristics.

# Dataset Attributes
The dataset includes the following attributes:
1. **Person ID**: Unique identifier for each individual.
2. **Gender**: Gender of the individual.
3. **Age**: Age of the individual.
4. **Occupation**: Job title or occupation of the individual.
5. **Sleep Duration**: Total hours of sleep per night.
6. **Quality of Sleep**: Subjective rating of sleep quality.
7. **Physical Activity Level**: Measure of daily physical activity.
8. **Stress Level**: Self-reported stress level.
9. **BMI Category**: Body Mass Index category.
10. **Blood Pressure**: Blood pressure reading.
11. **Heart Rate**: Heart rate in beats per minute.
12. **Daily Steps**: Number of steps taken daily.
13. **Sleep Disorder**: Presence of sleep disorders such as Sleep Apnea or Insomnia.

# Visualizations and Analysis

1. **Scatter Plot: Relationship between Sleep Duration and Sleep Quality**
   - This scatter plot visualizes the relationship between sleep duration and the subjective quality of sleep.

2. **Box Plot: Relationship between Physical Activity and Sleep Quality**
   - This box plot illustrates how physical activity levels influence the quality of sleep.

3. **Count Plot: Gender Distribution in Relation to Sleep Disorders**
   - The count plot showcases the distribution of genders with respect to various sleep disorders.

4. **Count Plot: BMI Category Distribution in Relation to Sleep Disorders**
   - This count plot visualizes the distribution of BMI categories and their relation to sleep disorders.

5. **Histogram: Count of People with Sleep Apnea, Insomnia, and None**
   - The histogram provides a visual representation of the number of individuals suffering from Sleep Apnea, Insomnia, and those without any sleep disorder.

6. **Tree Map: Visualization of Job Titles, Sleep Disorder, and Occupation**
   - A tree map representing the distribution of job titles, sleep disorders, and occupations within the dataset.

7. **Sunburst Display: Sleep Quality, Sleep Disorder, and Quality of Sleep**
   - A sunburst display that provides a multi-level visualization of sleep quality, sleep disorders, and the quality of sleep.

8. **Violin Plot: Relationship between Sleep Disorder and Physical Activity Level**
   - This violin plot demonstrates the distribution of physical activity levels among individuals with various sleep disorders.

9. **Empirical Distribution Function (EDF): Probability of Getting a Sleeping Disorder by Age**
   - This plot illustrates the probability of developing a sleep disorder as a function of age, using an Empirical Distribution Function.

# Requirements
To run the analysis and generate the plots, the following Python libraries are required:
- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `plotly`

# How to Run the Analysis
1. Ensure all required libraries are installed:
   ```bash
   pip install pandas matplotlib seaborn numpy plotly
   ```
2. Load the dataset into a pandas DataFrame.
3. Execute the provided Python script to generate the visualizations.
4. The plots will be saved to your working directory or displayed inline if using a Jupyter notebook.

# Conclusion
This project provides insights into the relationships between various factors such as sleep duration, physical activity, and sleep quality, and how these are associated with sleep disorders. The visualizations help in understanding these relationships and identifying patterns that might be of interest in further analysis.

This README provides an overview of your analysis project and detailed descriptions of the visualizations generated.
