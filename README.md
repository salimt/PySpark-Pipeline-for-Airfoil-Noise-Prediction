<p style="text-align:center">
    <a href="https://github.com/salimt">
    <img src="https://i.imgur.com/7bgtWRh.jpeg" width="200" alt="Skills Network Logo">
    </a>
</p>


## ML Pipeline for Airfoil noise prediction using PySpark


## Scenario


As a data engineer at an aeronautics consulting firm renowned for its efficient airfoil design for planes and sports cars, my role involves facilitating data preparation and constructing machine learning pipelines. In this project, we'll be working with a modified version of the NASA Airfoil Self Noise dataset. Our objective is to clean the dataset by removing duplicate rows and eliminating any entries with null values. Subsequently, we'll develop a machine learning pipeline to create a predictive model that estimates sound levels based on all other available columns. Following model evaluation, we'll finalize the process by persisting the model for future use.

## Objectives

### Part 1: Execute ETL Operations
- Load a CSV dataset.
- Eliminate any duplicate entries.
- Remove rows containing null values.
- Apply necessary transformations.
- Save the cleansed data in the Parquet format.

### Part 2: Construct a Machine Learning Pipeline
- Develop a machine learning pipeline for prediction.

### Part 3: Assess the Model
- Assess the model's performance using appropriate metrics.

### Part 4: Preserve the Model
- Save the model for future deployment purposes.
- Load and validate the stored model.



## Datasets

 - The original dataset can be found here NASA airfoil self noise dataset. https://archive.ics.uci.edu/dataset/291/airfoil+self+noise

Diagram of an airfoil. - For informational purpose


![Airfoil with flow](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_with_flow.png)


Diagram showing the Angle of attack. - For informational purpose


![Airfoil angle of attack](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-BD0231EN-Coursera/images/Airfoil_angle_of_attack.jpg)
