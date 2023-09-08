Salesforce Account Field Update and Lightning Component
This repository contains Salesforce code examples for performing the following tasks:

Create a field on Account named "Number of Contacts":

A custom field called "Number_of_Contacts__c" is created on the Account object.
This field is automatically populated with the number of contacts related to each account using triggers and automation.
Build a basic Lightning component:

A Lightning Web component named "recentAccounts" is developed.
The component queries and displays a list of the 10 most recently created accounts.
Make a basic HTTP callout and print the result:

A simple Apex class named "HttpCalloutExample" demonstrates making an HTTP callout to "https://postman-echo.com/get?foo1=bar1&foo2=bar2".
The response from the callout is printed to the debug logs using System.debug.
Prerequisites
Access to a Salesforce developer or sandbox environment.
Salesforce CLI for deploying the code to your environment (optional).
Installation and Usage
Creating the "Number of Contacts" Field:

Deploy the Apex trigger and class provided in the repository to your Salesforce environment.
Configure the trigger to run on Contact create, update, and delete events.
The "Number_of_Contacts__c" field on the Account object will be automatically updated.
Building and Using the Lightning Component:

Deploy the Lightning component to your Salesforce environment.
Create a Lightning App Page and add the "AccountList" component to it.
The component will display a list of the 10 most recently created accounts.
Making the HTTP Callout:

Deploy the Apex class "HttpCalloutExample" to your Salesforce environment.
Execute the makeHttpCallout method to make the HTTP callout and view the response in the debug logs.
Contributing
Feel free to contribute to this repository by opening issues or creating pull requests.

License
