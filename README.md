# HR-Attrition-Case-Study-using-Python-and-ML
### In this project, I developed a Machine Learning model using Logistic Regression to predict if the a set of employees from a mega-set of 14K+ employees will quit the job or not. 
### I drove data over Turnover Propensity Index (TPI) to classify each employess as unlikely, less likely, more likely, or most likely to quit the job.
### Finally, I concluded top 3 factors responsible for employee retention using Confusion matrix and Decision tree algorithm.
### Throughout the project, I produced various visualization charts to produce insightful results.  
### I have performed a different analysis in each and every section. After each analysis, I have presented a report summarizing all the observations of that particular section.
 
## 1. Firstly, I performed the Count Analysis of the Data in various ways like:
#### Analysis of salary with overall data:
![Screenshot (22)](https://user-images.githubusercontent.com/73714933/100615022-04b62680-333d-11eb-8754-18d59739b801.png)
#### Report:
We can see that the most number of employees are under the catagory of Low Salary. Also, we can interpret that there are relatively low number of employees whose salaries are considerd HIGH. We can sense this information naturally becouse people with high salary work on higher levels ie; they manage several number of employees under them.So the intution derived from the data is right.
 
#### Analysis of Department with overall Data:
![Screenshot (23)](https://user-images.githubusercontent.com/73714933/100615027-05e75380-333d-11eb-8829-547321d29fa1.png)
#### Report:
The insight that we gain from the above graph is that the number of employees working under the Sales department is highest. By this graph, we can know and compare workforces under different Departments.

#### Analysis of Departments with Salary:
![Screenshot (24)](https://user-images.githubusercontent.com/73714933/100615028-05e75380-333d-11eb-8d5e-9e97df446ca5.png)
#### Report:
By the above graph, we can analyze Salary Distribution of workforces under different Departments.

#### Analyzing Relation between Number of Projects with Salary:
![Screenshot (25)](https://user-images.githubusercontent.com/73714933/100615029-067fea00-333d-11eb-8adc-bc78d944c294.png)
#### Report:
Here, we can see that the most common number of projects handled by workers are 4 and 5. Here, we can also see that the most number of workers under projects are catogarized under the Low salary tag.

#### Analyzing Relationship between Number of Projects and Individual Departments:
![Screenshot (26)](https://user-images.githubusercontent.com/73714933/100615033-067fea00-333d-11eb-9aad-5a2b59d8f87f.png)
#### Report:
Here, we compare different different departments based on the number of projects undergoing in each and every one of them.

#### Analyzing Relationship between Time spent in the company by employees and their current Salary Tag:
![Screenshot (27)](https://user-images.githubusercontent.com/73714933/100615035-07188080-333d-11eb-934a-7c5128a8e446.png)
#### Report:
Here, we can see that for every salary tag, the most number of employees are of 3 year of experience in the company. A major workforce has spent 3 years in the same company.

#### Analyzing Work Accident data:
![Screenshot (28)](https://user-images.githubusercontent.com/73714933/100615036-07b11700-333d-11eb-9a84-80d4bdd6375a.png)
#### Report:
Here, we can see that the most number of work accidents that happened in the company are from the Sales Department.

#### Analyzing Number of Promotions in various Departments:
![Screenshot (29)](https://user-images.githubusercontent.com/73714933/100615040-07b11700-333d-11eb-8e4f-4d3ec8707189.png)
#### Report:
Here we can see that Most number of Promotion given in last 5 years are from sales department and lowest are from IT Department

## 2. After analyzing the dataset through various angles, I performed some Boxplot Analysis. 

#### Analyzing Satisfaction Range with Salary:
![Screenshot (30)](https://user-images.githubusercontent.com/73714933/100615042-0849ad80-333d-11eb-8d13-0203550f7ef5.png)
#### Report:
Here, we can see that the average number of employees with low salary tags are less satisfied as compared to high salary tag ones.

#### Analyzing Range of Average Working hours under Various Departments:
![Screenshot (31)](https://user-images.githubusercontent.com/73714933/100615044-08e24400-333d-11eb-9e55-db5c6ac38a99.png)
#### Report:
Here, we can see that almost every department works for the same duration of time.

#### Analyzing Satisfaction with years spent in the company:
![Screenshot (32)](https://user-images.githubusercontent.com/73714933/100615046-08e24400-333d-11eb-8f7e-36057752ea80.png)
#### Report:
Here, we can see that initially, the satisfication average reduces continuously for 4 years but we can see a high jump in the fifth year, and it remains the highest till 10 years. From this analysis, I can assume that may be, there is some kind of policy of the company for completing 5 years,there may be some benefits or compensation or promotion or may be some gifts are given to employees for spending 5 years. Perhaps, that's why, there is a sudden hike in the satisfaction average of employees.

#### Analyzing Quitting of jobs of People:
![Screenshot (33)](https://user-images.githubusercontent.com/73714933/100615049-097ada80-333d-11eb-9d6f-e3de89fab6a5.png)
#### Report:
Here, we can see that most number of people quit their job after 4 years. We can also see that the most unsatisfied workforce belongs to the group of 4 years experience. Therefore, company has to improve its policy and check on how they can ameliorate the work enviroment of people belonging to 4 years experience group.

## 3. Now, I did some Data Processing in which I categorized Satisfaction into labels and evaluated employees on last evaluation.
