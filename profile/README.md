# Quantified Student
The Quantified Student (QS for short) project focuses on helping students with their development and optimizing their performance with the help of collected data. The collected data will be shown in a dashboard where the student can see it. After which, the student can conclude where and how to improve their workflow. For example, the system can show when it is the best time to work for the student.

## Setup local dev env
1. Clone the repositories [QS-Backend-API](https://github.com/quantifiedstudent/QS-Backend-API), [QS-Gateway](https://github.com/quantifiedstudent/QS-Gateway), [QS-Dashbaord](https://github.com/quantifiedstudent/QS-Dashboard)

2. Dashboard
The dashboard currently works with a dummy database to gather data and is not linked to the actual gateway.
  2.1 first you have to install the dependancies using `npm i`
  2.2 then in order to run the project, run `npm run dev`
  2.3 and to run the dummy database run `npm run api`
  
3. QS-Backend-API
The backend api currently directly uses the provisioned database in azure. This is not ideal for an development environment and has to be fixed. But the project runs just in nodejs so in order to run it you
  3.1 install the dependancies with `npm i`
  3.2 run the project using `npm run dev`
  
 4. QS-Gateway
 In order to be able to make use of the QS-Backend-API you have to also have the QS-Gateway running because the request travels trough there.
  4.1 Install the depenancies using `npm i`
  4.2 run the project with `npm run dev`
