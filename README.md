# Technical Takehome Exercise

## Overview
This technical takehome exercise involves two parts. Part 1 is focused on querying the Metronome API to generate a customer summary report. The report is an overview of customers, current invoice balance, current credit balance and anything else you choose to include. In addition to the API, many clients leverage Metronome’s Data Export capabilities for reporting and reconciliation purposes. Part 2 involves building SQL against sample egress data. 

## Part 1: Query Metronome API to produce customer summary report


### Part One
The primary objectives of this part are as follows:
- Query the Metronome API to retrieve relevant customer data.
- Process the retrieved data to generate a summary report (csv).
- Include essential customer information such as customer name, customer invoice balance, credit balance, etc.
- Process the report to a single csv


### Instructions
Follow these steps to complete Part 1 of the exercise:
1. The Metronome team will provide an API key
2. Develop a script that makes the necessary API calls and processes the data down to the final csv
5. Ensure proper error handling and data validation throughout the process.
6. Document any assumptions made or limitations encountered during the development process.

### Deliverables
Upon completion of Part 1, submit the following:
- Source code of the script or program developed to query the Metronome API.
- Generated customer summary report
- README.md file documenting the approach, challenges, and any additional information relevant to the exercise.

### Resources
- [Metronome API documentation](https://docs.metronome.com/api/)
- [Metronome Documentation](https://docs.metronome.com/)


## Part 2: Query sample egress dataset for common client asks

### Part Two:
The primary objectives of this part are as follows:
- Demonstrate fundamental understanding of SQL and relational databases
- Produce reports based on common client scenarios

### Instructions
Follow these steps to complete Part 2 of the exercise:
1. Use the sample egress data in the folder Sample Egress Data. Each csv corresponds to a table in the data export schema.
2. Write SQL queries for the following three scenarios:

   (a) _Number of images generated between March 10th and 25th, 2024 by image size._ The client has several billable metrics defined to track the number of images created by size. A sample of one of the billable metric definitions is pictured below:

   <img width="316" alt="image" src="https://github.com/mcough2/SA-takehome/assets/149521888/41e60a9b-7c35-4bba-b67c-249fe6c087f4">
   
   Using the sample egress data provided, write a query that calculates the total number of images that were generated for each size between March 10th and March 25th (inclusive). 

   (b) _Recreate the March invoice for customer A1 Company._  Write a query that returns a list of all the charges (description, quantity, unit price, total) for the finalized March invoice for customer A1 Company. The screenshot below provides a sample of a February finalized invoice. The query should return the corresponding lines under the CPU Hours and Storage products for March.

   <img width="858" alt="image" src="https://github.com/mcough2/SA-takehome/assets/149521888/fd0addad-1e3f-479c-ad4f-1461493a213c">


   (c) _Generate a report of billings by Plan for the month of March 2024_ 


### Deliverables
Upon completion of Part 2, submit the following:
- SQL queries for each of the three scenarios outlined in the Instructions above
- Screenshots or CSVs of output of executing the queries against the sample data
- README.md file documenting the approach, challenges, and any additional information relevant to the exercise.

### Resources
- [Metronome Data Export](https://docs.metronome.com/developer-resources/export-metronome-data/)
- [Entity Relationship Diagram](https://docs.metronome.com/developer-resources/entity-relationship-diagram/)

# Additional Notes
- This exercise aims to assess your ability to work with APIs, process data, and create reports
- Focus on code readability, efficiency, and adherence to best practices.
- Feel free to reach out for clarification or assistance during the exercise.
- Have fun and enjoy the challenge!

