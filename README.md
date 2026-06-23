# Bhavesh_Project_1
Problem Statement:
Develop an AI-powered Employee Learning and Assessment ChatBot using Python that serves as a centralized platform for training material access, learning tracking, and automated assessment.

The chatbot should first collect employee details such as Employee ID, Employee Name, and Department, and store this information in an Excel database. After registration, the employee should be presented with a list of available training documents (PDFs) through a checkbox-style selection interface. Based on the employee's selection, the corresponding PDF should be made available for download and reading.

The chatbot should then ask the employee whether they would like to Read the Material or Take the Test. To ensure proper learning compliance, an employee should only be allowed to attempt the test if the corresponding PDF has already been downloaded/read.

For assessments, the system should use AI techniques to automatically generate questions from the selected PDF content. Each test should contain unique questions to minimize repetition and encourage genuine understanding. The duration of the test should be dynamically set based on the selected training document.

Upon completion of the assessment, the chatbot should automatically evaluate the responses, calculate the score, and display the final marks to the employee. The employee's test score, along with their previously collected details, should then be updated and stored in the Excel database for future reference and reporting.
