# Employee Correlation Analysis | Python & Jupyter Notebook

<img width="881" alt="Screenshot 2024-10-21 at 11 47 37 PM" src="https://github.com/user-attachments/assets/47de3ef3-4e64-492d-a1cc-52316debb273">

# Project Background

Does the number of years employed have any direct correlation to the overall number of employees retained vs left.
Is there a point in which x-amount years employeed has a significant shift of employees leaving the company vs
retained. Our analysis will consists upon the bases of two clear distinctions, where years employeed (>=5 and <=5)
The purpose of this project is to determine if there are any correlations with hours worked, projects completed,
and satisfaction levels amongst employees. Once our analysis is complete, we will take another step by seperating
our analysis into departments in order to create insights to see if there are any correlations amongst departments

Insights and recommendations are provided on the following key areas:

* Create summary statistics for each variable needed
* Visualize the left vs retained results based on >=5 and <=5 years employed
* Visualize the correlations with variables SATISFACTION LEVELS, NUMBER PROJECTS, AVERAGE MONTHLY HOURS
* Visualize the correlations with same variables grouped by DEPARTMENT

Full in-depth project can be found [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/blob/main/Employee%20Correlation%20Analysis.ipynb)

Project dataset can be found [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/tree/main/Project%20Files)

Below consists of major key highlights of entire project

# Data Structure & Initial Checks

Overview of dataset used in project:

<img width="401" alt="Screenshot 2024-10-22 at 12 01 09 AM" src="https://github.com/user-attachments/assets/4f32cd79-0681-4066-9137-e537ab24e1e1">


<img width="1127" alt="Screenshot 2024-10-22 at 12 00 07 AM" src="https://github.com/user-attachments/assets/38a19cc6-6e6f-402f-9125-488a30edc751">

Prior to beginning of analysis, familiarization with the dataset was used for quality control

# Executive Summary

Overview of findings: 

Summary: Time spent with the company results

Part 3 Summary: Correlation results amongst 'satisfaction_level', 'number_project', 'average_monthly_hours'

Satisfaction level scale: **0.0 - 1.0**

* Where years >=5 & left averages:
'satisfaction_level'= .73, 'number_project'= 4.7, 'average_monthly_hours'= 245

* Where years >=5 & retained averages:
'satisfaction_level'= .55, 'number_project'= 4, 'average_monthly_hours'= 197

* Where years <=5 & left averages:
'satisfaction_level'= .41, 'number_project'= 3.8, 'average_monthly_hours'= 205

* Where years <=5 & retained averages:
    'satisfaction_level'= .67, 'number_project'= 3.8, 'average_monthly_hours'= 199

Employees who eventually left the company averaged the highest satisfaction levels, projects completed, and average hours worked monthly. We can safely assume other factors such as better oppertunity arose for the most productive and most satisfied employees to eventually depart.

Example shown below of satisfaction level shifts at the 3 and 4 year mark

<img width="1452" alt="Screenshot 2024-10-22 at 12 12 10 AM" src="https://github.com/user-attachments/assets/02f994b4-d02e-4e13-8d12-1e50080a2a81">

# Insights & Deep Dive

* Left company percentage when years employed >= 5 

<img width="1459" alt="Screenshot 2024-10-23 at 11 40 49 AM" src="https://github.com/user-attachments/assets/81383f0b-26f2-4f56-9a14-7b0e82195374">

* Retained percentage when years employed >= 5 

<img width="1246" alt="Screenshot 2024-10-23 at 11 42 43 AM" src="https://github.com/user-attachments/assets/a74df8e7-2a4a-4686-9516-b6378793c063">

* Left company percentage when years employed <= 5 

<img width="1244" alt="Screenshot 2024-10-23 at 11 44 05 AM" src="https://github.com/user-attachments/assets/76ccd337-7d42-43ac-a15d-eb3ad73385d5">

* Retained percentage when employed <= 5 

<img width="1254" alt="Screenshot 2024-10-23 at 11 45 57 AM" src="https://github.com/user-attachments/assets/77d5b63a-9f91-471b-8d5d-7040f8ec530a">

Overview of variable correlation (**satisfaction levels, number of projects, average monthly hours worked**) with respect to years employed

Left company when years employed >= 5

<img width="249" alt="Screenshot 2024-10-23 at 11 57 05 AM" src="https://github.com/user-attachments/assets/761fd71b-ee38-4790-b1c2-29818e1c3eb2">

Retained when years employed >= 5

<img width="250" alt="Screenshot 2024-10-23 at 11 57 49 AM" src="https://github.com/user-attachments/assets/7313458c-5f95-4184-bd6a-fab3ea4da81c">

Left company when years employed <= 5

<img width="247" alt="Screenshot 2024-10-23 at 11 58 08 AM" src="https://github.com/user-attachments/assets/4aae73ed-a47b-482d-a47a-ba107961a6df">

Retained when years employed <= 5

<img width="246" alt="Screenshot 2024-10-23 at 11 58 17 AM" src="https://github.com/user-attachments/assets/b3943ca1-dccd-4944-b116-ceaea981a066">

Visualization of variable correlation (**satisfaction levels, number of projects, average monthly hours worked**) by **department**

Left company when years employed >= 5












