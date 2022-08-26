# Bank-Marketing
DATASET OVERVIEW
The data is related with direct marketing campaigns of a Portuguese banking institution. We 
propose a data mining approach to forecast the success of the telemarketing campaign. The 
classification goal is to predict if the client will subscribe a term deposit.
The dataset used has a total of 45,211 instances, each one representing an individual client. For 
each instance, we are given 16 features describing the details about the client.
The data is multivariate and of the 17 features, 7 are numerical, 6 are categorical and 4 are 
binary.

ATTRIBUTE INFORMATION
INPUT VARIABLES:
Bank Client Data:
1. age (numeric)
2. job: type of job (categorical) Values: "admin.", "unknown", "unemployed", 
"management", "housemaid", "entrepreneur", "student", "blue-collar", "selfemployed", "retired", "technician", "services"
3. marital: marital status (categorical) Values: "married", "divorced", "single" (Note: 
"divorced" means divorced or widowed)
4. education (categorical) Values: "unknown", "secondary", "primary", "tertiary"
5. default: has credit in default? (binary) Values: "yes”, “no"
6. balance: average yearly balance, in euros (numeric)
7. housing: has housing loan? (binary) Values: "yes”, “no"
8. loan: has personal loan? (binary) Values: "yes”, “no"

Related With The Last Contact Of The Current Campaign:

9. contact: contact communication type (categorical) Values: "unknown”, “telephone”, 
“cellular"
10. day: last contact day of the month (numeric)
11. month: last contact month of year (categorical) Values: "jan", "feb", "mar", ..., "nov", 
"dec"
12. duration: last contact duration, in seconds (numeric)

Other Attributes:

13. campaign: number of contacts performed during this campaign and for this client 
(numeric) Note: Includes last contact
14. pdays: number of days that passed by after the client was last contacted from a 
previous campaign (numeric) Note: ‘-1’ means client was not previously contacted
15. previous: number of contacts performed before this campaign and for this client 
(numeric)
16. poutcome: outcome of the previous marketing campaign (categorical) Values: 
"unknown”, “other”, “failure”, “success"

OUTPUT/TARGET VARIABLE:

17. y - has the client subscribed a term deposit? (binary) Values: "yes”, “no"
