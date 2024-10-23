# Employee Correlation Analysis | Python & Jupyter Notebook

Full in-depth project can be found [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/blob/main/Employee%20Correlation%20Analysis.ipynb)

Project dataset can be found [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/tree/main/Project%20Files)

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

Example shown below of satisfaction level shifts occuring at the 3 and 4 year mark

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

**Average satisfaction levels + trend over time**

<img width="1454" alt="Screenshot 2024-10-23 at 12 13 10 PM" src="https://github.com/user-attachments/assets/231eacd5-1e0a-4c04-878f-2d09022819c2">

<img width="1449" alt="Screenshot 2024-10-23 at 12 13 24 PM" src="https://github.com/user-attachments/assets/caece2f7-adb3-4832-915a-c857f0e24d43">

**Average number of projects + trend over time**

<img width="1439" alt="Screenshot 2024-10-23 at 12 16 21 PM" src="https://github.com/user-attachments/assets/f62b863b-1424-444c-978e-e40eccccbda8">

<img width="1450" alt="Screenshot 2024-10-23 at 12 16 33 PM" src="https://github.com/user-attachments/assets/704d59ef-08b7-4de2-8a32-c02d3ad748b1">

**Average monthly hours worked + trend over time**

<img width="1453" alt="Screenshot 2024-10-23 at 12 19 22 PM" src="https://github.com/user-attachments/assets/bb81730c-8470-4ad0-9d56-087c0cae92c5">

<img width="1458" alt="Screenshot 2024-10-23 at 12 19 34 PM" src="https://github.com/user-attachments/assets/2723f714-9289-43d6-98a5-54807afb465b">

Retained when years employed >= 5

**Average satisfaction levels + trend over time**

<img width="1449" alt="Screenshot 2024-10-23 at 12 24 53 PM" src="https://github.com/user-attachments/assets/5e8d7fec-a1f8-4de6-824f-a44e7a1c7754">

<img width="1449" alt="Screenshot 2024-10-23 at 12 25 04 PM" src="https://github.com/user-attachments/assets/b486fcbb-e648-4522-9609-7e0fd49368f4">

**Average number of projects + trend over time**

<img width="1441" alt="Screenshot 2024-10-23 at 12 25 42 PM" src="https://github.com/user-attachments/assets/c557547e-5531-4e8a-9c26-3f15a9afc572">

<img width="1451" alt="Screenshot 2024-10-23 at 12 25 50 PM" src="https://github.com/user-attachments/assets/2de52255-6063-4535-ba81-1d206ba80046">

**Average monthly hours worked + trend over time**

<img width="1452" alt="Screenshot 2024-10-23 at 12 26 27 PM" src="https://github.com/user-attachments/assets/d200698d-9040-4d23-bc1f-178ec7c510ff">

<img width="1455" alt="Screenshot 2024-10-23 at 12 26 35 PM" src="https://github.com/user-attachments/assets/ea924a92-08c0-4611-834d-c7ab37cefe0a">

Left company when years employed <= 5 

**Average satisfaction levels + trend over time**

<img width="1449" alt="Screenshot 2024-10-23 at 12 42 19 PM" src="https://github.com/user-attachments/assets/da47de87-e9dc-4cb4-a220-b3703a0677e7">

<img width="1452" alt="Screenshot 2024-10-23 at 12 42 37 PM" src="https://github.com/user-attachments/assets/95cf0ecd-e25f-4e66-971e-897f7b255e66">

**Average number of projects + trend over time**

<img width="1453" alt="Screenshot 2024-10-23 at 12 43 16 PM" src="https://github.com/user-attachments/assets/51902d5f-2fdb-490f-b069-55dbc433912f">

<img width="1441" alt="Screenshot 2024-10-23 at 12 43 23 PM" src="https://github.com/user-attachments/assets/00b61846-d05b-4de9-99e4-4bbc75ec992a">

**Average monthly hours worked + trend over time**

<img width="1454" alt="Screenshot 2024-10-23 at 12 43 53 PM" src="https://github.com/user-attachments/assets/f31fa4eb-bf0a-4450-88a4-d03050555a19">

<img width="1456" alt="Screenshot 2024-10-23 at 12 43 59 PM" src="https://github.com/user-attachments/assets/d7e96e4b-09c4-4674-aadf-5a1fdae0a161">

Retained when years employed <= 5

**Average satisfaction levels + trend over time**

<img width="1452" alt="Screenshot 2024-10-23 at 12 45 31 PM" src="https://github.com/user-attachments/assets/0d9591d8-4097-4937-b4fb-95aa768c627a">

<img width="1454" alt="Screenshot 2024-10-23 at 12 45 38 PM" src="https://github.com/user-attachments/assets/64b0563f-1640-4113-9bb6-a084ded77863">

**Average number of projects + trend over time**

<img width="1452" alt="Screenshot 2024-10-23 at 12 46 05 PM" src="https://github.com/user-attachments/assets/24051241-2c39-4b1f-851f-0565b59e54b1">

<img width="1450" alt="Screenshot 2024-10-23 at 12 46 14 PM" src="https://github.com/user-attachments/assets/e9bee177-b267-4e4b-9122-2c50927c8739">

**Average monthly hours worked + trend over time**

<img width="1453" alt="Screenshot 2024-10-23 at 12 46 46 PM" src="https://github.com/user-attachments/assets/10a6275e-7318-427a-8cd9-26cd0170f2ef">

<img width="1455" alt="Screenshot 2024-10-23 at 12 46 54 PM" src="https://github.com/user-attachments/assets/afe0dd33-0c73-4d8b-aee1-7b9e42a4e2e1">

# Conclusion

Brief overview:

* 3571(24%) left / 11428(76%) retained when years employed was >=5
* 3 years (43%) / 8 years (10%) were the highest/lowest time spend with the company
* 4 projects (29%) / 7 projects (2%) were the highest / lowest amount of projects completed
* 135 & 156 hours / 303 hours were the highset / lowest average of monthly hours worked
* Sales(28%) / management(4%) were the most / least employees per department

Potential correlation amongst departments of 'satisfaction_level', 'number_project', 'average_monthly_hours'

Where years >=5 & left
* Highest 'satisfaction_level' = management & product_mng
* Lowest 'satisfaction_level' = IT, RandD, hr
* Highest 'number_project' = IT & RandD
* Lowest 'number_project' = management
* Highest 'average_monthly_hours' = IT & marketing
* Lowest 'average_monthly_hours' = hr, product_mng, support

Where years >=5 & retained
* Highest 'satisfaction_level' = IT, management, sales
* Lowest 'satisfaction_level' = RandD, hr
* Highest 'number_project' = RandD, product_mng, sales, technical
* Lowest 'number_project' = IT, management, marketing
* Highest 'average_monthly_hours' = RandD, accounting, hr, sales
* Lowest 'average_monthly_hours' = marketing, support

Where years <=5 & left
* Highest 'satisfaction_level' = RandD, product_mng, support
* Lowest 'satisfaction_level' = accounting
* Highest 'number_project' = management, technical
* Lowest 'number_project' = hr, marketing
* Highest 'average_monthly_hours' = IT, RandD, management, technical
* Lowest 'average_monthly_hours' = hr, marketing

Where years <=5 & retained
* Highest 'satisfaction_level' = IT, marketing, support, technical
* Lowest 'satisfaction_level' = accounting
* Highest 'number_project' = management
* Lowest 'number_project' = hr
* Highest 'average_monthly_hours' = almost no difference
* Lowest 'average_monthly_hours' = almost no difference

There is no distinct correlation amongst departments regarding the variables 'satisfaction_level', 'number_project', 'average_monthly_hours'

Full in-depth project can be found again [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/blob/main/Employee%20Correlation%20Analysis.ipynb)

Project dataset can be found again [here](https://github.com/Kahvedzic/Employee-Correlation-Analysis-/tree/main/Project%20Files)

# Thank You

Amar Kahvedzic

