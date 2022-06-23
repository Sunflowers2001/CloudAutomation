### Hi there 👋, Maryam.Gokalp
#### QA tester & methodologies
![QA tester & methodologies](https://github.com/Sunflowers2001/Sunflowers2001/blob/main/Screenshot%202022-04-24%20at%2010.36.42.png?raw=true)

I am Maryam Gokalp from South America, and I specialise in system development lifecycle experience, including designing, developing and implementing test plans and test cases.

Skills: Test Plans, Cases & Process/Regression Testing/ Performance/ Testing Automation/Defect & Bug Tracking / HTML / CSS/etc...

## Skills and Experience

⚛ React

💻 HTML, 

CSS,


Simple-cucumber-demo

Basic cucumber framework used for running automation tests on Jenkins.

Running locally

To run locally and generate HTML reports, use this maven goal verify. HTML reports should be generated under target/cucumber-html-reports

mvn verify

Jenkins

Install Cucumber HTML report plugin. Create a simple job and use this repository in the repository url field. In the post build actions, select option Cucumber reports and point to the location of the cucumber json report. Run the project as a maven goal test.

mvn test

Tags

You can pass a custom tag using terminal. Available tags are @smoke, @regression.

mvn test -CloudAutomation.filter.tags="@smoke"

Browsers

You can pass change using command line argument BROWSER

mvn test -DBROWSER=firefox


