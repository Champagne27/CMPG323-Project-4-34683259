# CMPG323-Project-4-34683259
# Project Overview
This repository contains the implementation of the NWU Tech Trends Telemetry Portal - User Acceptance Testing automation. The automation has been developed using UiPath and is intended to assist in the user acceptance testing (UAT) phase by automating the process of reading telemetry data from an Excel file, submitting it to a web application, and recording the results of the testing.

## Table of Contents
1. [Project Progress](#project-progress)
2. [Project Setup](#project-setup)
3. [User Acceptance Testing](#user-acceptance-testing)
4. [UI Automation](#ui-automation)
5. [Record Results](#record-results)
6. [Project Close-out](#project-close-out)
7. [Project Documentation](#project-documentation)
8. [Reference List](#reference-list)

## Project Progress
#### Source Control Management:
Ensure that the solution is committed and pushed to source control throughout the project lifecycle.
Continuously update the GitHub project to reflect progress, showcasing the iterative development process.

## Project Setup
- Create a repository
- Clone  GitHub repository
- Install UiPath Studio
- Create a new UiPath process named 'NWU Tech Trends Telemetry Portal – User Acceptance Testing'

  ## User Acceptance Testing
- Read the input data from Excel into a data table in UiPath.
- Ensure that the data is readable and iterated over in UiPath.

  ## UI Automation
- For each record in the data table, navigate to the URL in the browser that allows data entry to create a new record.
- Insert the fields from each record into the fields on the web application to create a new record.
- Click the 'submit' button on the web application to create a new record.
- Navigate to the URL where you can view the newly created record on the web application.

  ## Record Results
- If the item was created successfully, update the data table record to indicate a pass.
- If the item was not created, update the data table to indicate a failure.
- Update the Excel spreadsheet with the testing results in the 'Test Results' column.

## Project Close-out
- Deploy Solution
  - Publish the UiPath solution to the UiPath Orchestrator.
 
    
## Reference List
1.  UiPath (2023). UiPath Documentation. [Online] Available at: https://docs.uipath.com/
2.  Alexander, M., & Walkenbach, J. (2016). Excel VBA Programming for Dummies. Publisher.
3.  Software Testing Fundamentals (2023). [Online] Available at: http://softwaretestingfundamentals.com/
4. UiPath Academy (2023). Robotic Process Automation - UiPath. [Online] Available at: https://academy.uipath.com/
5. Microsoft (2023). Microsoft Excel Docs. [Online] Available at: https://support.microsoft.com/en-us/excel
6. TechTarget (2022). UAT Best Practices Guide. [Online] Available at: https://searchsoftwarequality.techtarget.com/tutorial/User-Acceptance-Testing-UAT-Guide
7. Jenkins. (2023). Jenkins Documentation. [Online] Available at: https://www.jenkins.io/doc/
