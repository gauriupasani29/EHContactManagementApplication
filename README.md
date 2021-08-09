The solution contains 4 projects as below:
1. ContactManagementReactApp
   This project contains AddContact (responsible for adding new contact), UpdateContact(responsible for updating the contact), ListContacts (display a list of contacts with delete, deactivate and update options) components inside "Components" folders. 
2. EHContactmanagementAPI
   This project contains Rest APIs to add, update, delete, deactivate and list the contacts.
   Inside startup.cs dependency injection is used.
3. EHRepository
   This project has below folders
   a. Generic Repository: This folder contains Generic repository classes and interfaces.
   b. Contacts Repository: This folder contains Contacts repository classes and interfaces.
   c. Models: This folder has automatically generated classes using Entity framework and Db Context file.
      database first approach is used for generating the model classes. To use this, execute below script in SQL and update the connection string.
4. EHXUnitTests
   This project has Unit Test cases written for repository.
