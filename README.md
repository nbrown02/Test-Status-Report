# Test Status Report
Test Status Report is a Power BI template where you can enter your Azure DevOps details to generate a report that provide better insights into Test Cases and their status, in particular when looking at their traceability to Product Backlog Items (PBIs) and User Stories.

The types of questions to ask when using this report are:
* How much testing is complete?
* What is the current status of tests passing, failing, or being blocked?
* How many tests are defined for each PBI/User Story? 
* How many of these tests are passing?
* Which PBIs/User Stories are at risk?
* Which PBIs/User Stories aren't sufficiently stable for release?
* Which PBIs/User Stories can we ship today?

### Prerequisites
* [Make sure you have the latest version of Power BI Desktop](https://aka.ms/pbiSingleInstaller)
* Download the .pbit file
* Then you're good to get started!

### Connectivity
* Open the .pbit file
* Add your Organization and Project Name - this will be in your Azure DevOps URL https://dev.azure.com/{OrganizationName}/{ProjectName}/ 
* Hit load (note: you may get prompted for a login here, choose organisational account and enter your Azure DevOps email)
* Voila - your report is created!

### Screenshots
![alt text](https://raw.githubusercontent.com/nbrown02/Test-Status-Report/master/Screenshots/Picture1.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Test-Status-Report/master/Screenshots/Picture2.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Test-Status-Report/master/Screenshots/Picture3.png)

![alt text](https://raw.githubusercontent.com/nbrown02/Test-Status-Report/master/Screenshots/Picture4.png)

### FAQs
Why do I get a blank table on the traceability page? 
This is down to how Microsoft have built Azure DevOps, specifically with regards to test cases. Any test cases that have been manually linked to PBI’s / User Stories will not pull through in this report. In order to get the benefits of this report, you need to ensure you add test cases via the Kanban board. If you really want historical data, you can add test cases to old items, then the other test cases will pull through, so you can get this to work even if it does not initially populate - just needs some data quality efforts!  

### References
[Check out the Azure DevOps & Power BI OData guidance if interested in creating similar reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-test-plans-progress-status?view=azure-devops&tabs=powerbi)
