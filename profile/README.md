# Quantified Student
The Quantified Student (QS for short) project focuses on helping students with their development and optimizing their performance with the help of collected data. The collected data will be shown in a dashboard where the student can see it. After which, the student can conclude where and how to improve their workflow. For example, the system can show when it is the best time to work for the student.

## Setup Local Development Environment
1. Clone the repositories [Canvas Data Microservice](https://github.com/quantifiedstudent/CanvasDataMicroservice), [Weather Data Microservice](https://github.com/quantifiedstudent/WeatherDataMicroservice), [Analyse Microservice](https://github.com/quantifiedstudent/AnalyseMicroservice), [Dashboard](https://github.com/quantifiedstudent/Dashboard)

2. Canvas Data Microservice
    - Add [Canvas Access Token](https://canvas.instructure.com/doc/api/file.oauth.html#manual-token-generation) to the file PrivateToken.txt
    - Install all dependencies using `npm i`
    - Run the project with `npm run start:dev`
  
3. Weather Data Microservice
    - Install all dependencies using `npm i`
    - Run the project with `npm run start:dev`
  
4. Analyse Microservice
    - Install all dependencies using `npm i`
    - Run the project with `npm run start:dev`

5. Dashboard
    - Install all dependencies using `npm i`
    - Run the project with `npm run dev`
