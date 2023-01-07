# *Machine Learning 3 - Amazon.com Employee Access Challenge*

In this project, We will need to predict an emaployy's access needs, given his/her job role.
This is a dataset from Amazon


Here we will be using the *Catboost* Library, See Data Visualization, Cross Validation, Feature Importance, Build Model and Accuracy.

--------------------------------------------------------

ALTERNATIVELY

We will also use Logistic Regression along with Onehot Encoder to achieve the same.

-------------------------------------------------------

REFER CatBoost Documentation - https://catboost.ai/ <br>
(CatBoost is a high-performance open source library for gradient boosting on decision trees, this library can handle categorical variables with ease without transforming)

![image](https://user-images.githubusercontent.com/112689649/211143300-8aa6e23d-c0f6-483a-b288-050d5fe0c2e8.png)
![image](https://user-images.githubusercontent.com/112689649/211147614-08c9c699-4579-4b22-9130-5938f91e4402.png)



DATASET - https://www.kaggle.com/c/amazon-employee-access-challenge

## Dataset Description:<br>
The data consists of real historical data collected from 2010 & 2011.  Employees are manually allowed or denied access to resources over time. You must create an algorithm capable of learning from this historical data to predict approval/denial for an unseen set of employees. 

## File Descriptions <br>
train.csv - The training set. Each row has the ACTION (ground truth), RESOURCE, and information about the employee's role at the time of approval<br>

test.csv - The test set for which predictions should be made.  Each row asks whether an employee having the listed characteristics should have access to the listed resource.

## Dataset Information : <br>

When an employee at any company starts work, they first need to obtain the computer access necessary to fulfill their role. This access may allow an employee to read/manipulate resources through various applications or web portals. It is assumed that employees fulfilling the functions of a given role will access the same or similar resources. It is often the case that employees figure out the access they need as they encounter roadblocks during their daily work (e.g. not able to log into a reporting portal). A knowledgeable supervisor then takes time to manually grant the needed access in order to overcome access obstacles. As employees move throughout a company, this access discovery/recovery cycle wastes a nontrivial amount of time and money.

There is a considerable amount of data regarding an employee’s role within an organization and the resources to which they have access. Given the data related to current employees and their provisioned access, models can be built that automatically determine access privileges as employees enter and leave roles within a company. These auto-access models seek to minimize the human involvement required to grant or revoke employee access.

## Column Descriptions

Column Name	--> Description

* ACTION	--> ACTION is 1 if the resource was approved, 0 if the resource was not
* RESOURCE	--> An ID for each resource
* MGR_ID	--> The EMPLOYEE ID of the manager of the current EMPLOYEE ID record; an employee may have only one manager at a time
* ROLE_ROLLUP_1	--> Company role grouping category id 1 (e.g. US Engineering)
* ROLE_ROLLUP_2	--> Company role grouping category id 2 (e.g. US Retail)
* ROLE_DEPTNAME	--> Company role department description (e.g. Retail)
* ROLE_TITLE	--> Company role business title description (e.g. Senior Engineering Retail Manager)
* ROLE_FAMILY_DESC	--> Company role family extended description (e.g. Retail Manager, Software Engineering)
* ROLE_FAMILY	--> Company role family description (e.g. Retail Manager)
* ROLE_CODE	--> Company role code; this code is unique to each role (e.g. Manager)

---------------------------------------------------------------------------------------------------------------------------------


