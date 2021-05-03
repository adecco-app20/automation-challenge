Welcome to the Automation Coding challenge. Please read carefully the instructions and if you have any questions don't hesitate to ask.

### Instructions

You need to create an automation project that mimics the below steps. Your project should maximize browser coverage and leverage the Behavior Driven Development Framework.

There is no restriction for programming languages or frameworks.

### Steps to Automate

1. Navigate to the link: https://developer.salesforce.com/docs/component-library/documentation/en/48.0/lwc
2. Switch to the Component Reference tab
3. Search in Quick Find for “datatable”
4. Under Lightning Web Components, click on the Components>lightning>“datatable” on the left menu panel
5. Under Example tab on the main pane > select “Datatable with Inline Edit” from the dropdown
6. Click "run" -> Edit/Update the values for all the columns in row 3 in the table -

- Label: Larry Page
- Website: https://google.com
- Phone number:(555)-755-6575
- Date Time: Jan 01, 2022 12:57 PM
- Balance: 770.54

7. Assert the above have been updated in the table
8. Repeat step 5 by selecting the “Datatable with Sortable Column” from the dropdown
9. Click on the "Age" column and sort it
10. Assert the smaller age is at the top or bottom
11. Click on the "Age" column and sort it
12. Assert the smaller age is at the top or bottom

Please provide a GitHub/Bitbucket or alternative link to your repository with your automation project.

Note:

You must use at least 5 different types of selectors(ex: CSS, partial link text, link text, XPath(absolute and relative)) and 3 different types of assertions
If you face any challenge asserting any value from the table, skip that step
