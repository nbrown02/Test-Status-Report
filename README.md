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


### References
[Check out the Azure DevOps & Power BI OData guidance if interested in creating similar reports](https://docs.microsoft.com/en-us/azure/devops/report/powerbi/sample-test-plans-progress-status?view=azure-devops&tabs=powerbi)
