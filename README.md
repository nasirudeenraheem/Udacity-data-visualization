# Udacity-data-visualization

This is my final project on Udacity Data Analyst Nanodegree.

#### Domain

The analysis is focused on **Healthcare** Analytics.

### Objectives

1. Practise the core principles of data analysis

2. Gather information from the data using uni-variate, bivariate and multi-variate analysis

3. Use question, code and observation method.

4. Generate 15 insights from the dataset.

#### Dataset Link

The dataset link can be found on kaggle - https://www.kaggle.com/datasets/anmolkumar/janatahack-healthcare-analytics-part-2

#### Data Dictionary


<table>
<tr>
<td>Column</td>
<td>Description</td>
</tr>
<tr>
<td>case_id</td>
<td>Case_ID registered in Hospital</td>
</tr>  
<tr>
<td>Hospital_code</td>
<td>Unique code for the Hospital</td>
</tr> 
<tr>
<td>Hospital_type_code</td>
<td>Unique code for the type of Hospital</td>
</tr> 
 <tr>
<td>City_Code_Hospital</td>
<td>Code of the Hospital</td>
</tr> 
<tr>
<td>Hospital_region_code</td>
<td>Region Code of the Hospital</td>
</tr> 
<tr>
<td>Available Extra Rooms in Hospital</td>
<td>Number of Extra rooms available in the Hospital</td>
</tr> 
<tr>
<td>Department</td>
<td>Department overlooking the case</td>
</tr> 
<tr>
<td>Ward_Type</td>
<td>Code for the Ward type</td>
</tr> 
<tr>
<td>Ward_Facility_Code</td>
<td>Code for the Ward Facility</td>
</tr> 
<tr>
<td>Bed Grade</td>
<td>Condition of Bed in the Ward</td>
</tr> 
<tr>
<td>patientid</td>
<td>Unique Patient Id</td>
</tr> 
<tr>
<td>City_Code_Patient</td>
<td>City Code for the patient</td>
</tr> 
<tr>
<td>Type of Admission</td>
<td>Admission Type registered by the Hospital</td>
</tr> 
<tr>
<td>Severity of Illness</td>
<td>Severity of the illness recorded at the time of admission</td>
</tr>
<tr>
<td>Visitors with Patient</td>
<td>Number of Visitors with the patient</td>
</tr> 
<tr>
<td>Age</td>
<td>Age of the patient</td>
</tr>
<tr>
<td>Admission_Deposit</td>
<td>Deposit at the Admission Time</td>
</tr>
<tr>
<td>Stay</td>
<td>Stay Days by the patient</td>
</tr> 
</table>

### Problem Statement

The recent Covid-19 Pandemic has raised alarms over one of the most overlooked area to focus: Healthcare Management. While healthcare management has various use cases for using data science, patient length of stay is one critical parameter to observe and predict if one wants to improve the efficiency of the healthcare management in a hospital.

This parameter helps hospitals to identify patients of high LOS risk (patients who will stay longer) at the time of admission. Once identified, patients with high LOS risk can have their treatment plan optimized to minimize LOS and lower the chance of staff/visitor infection. Also, prior knowledge of LOS can aid in logistics such as room and bed allocation planning.

Suppose you have been hired as Data Scientist of HealthMan – a not for profit organization dedicated to manage the functioning of Hospitals in a professional and optimal manner.
The task is to accurately predict the Length of Stay for each patient on case by case basis so that the Hospitals can use this information for optimal resource allocation and better functioning. The length of stay is divided into 11 different classes ranging from 0-10 days to more than 100 days.

#### Dataset summary

1. The dataset has a total rows of 318438 and total columns of 18

2. It consists of 9 numeric and 9 categorical features. 

3. There are 2 columns with missing values but they are less than 5% of the entire data set rows.

4. The data is Tidy because we did not have any structural issues.

#### Data Wrangling process

1. The missing rows are drop from the dataset

2. The categorical variables that are ordinal in nature are converted using pandas Categorical Dtype

#### Plot used

In the exploratory data analysis process, Bar-chart, Histogram, Violin plot, Heatmap, Box plot, Line plot, Grid plot are used.

#### Questions asked from the dataset

##### Univariate Analysis

1. For How long did Patient **Stay**?
2. Which Ward Type admit patient the most and least in time of their stays in the hospital?
3. Which Department has the most admitted patient?
4. Which Severity of Ilness brought most patient to the Hospital?
5. Top 5 most visting patient code admitted.
6. Which type of hospital is visted the most?
7. Age group frequency.
8. Admission Deposit Distribution

##### Bivariate Analysis

9. Which type of **Severity of Ilness** as **the most Stay**
10. Average Admission deposit per Severity of Ilness in the Hospital.
11. Department distribution in **Age** and **Hospital_region_code**
12. Type of admission per **Stay**

##### Multi-Variate Analysis

13. Age distribution per Admission Deposit and Severity of Illness.
14. Stay vs Ward type vs Admission Deposit.
15. Correlation analysis of the numeric data.

#### Findings
1. 
