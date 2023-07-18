# Summer_Project (Transport Management System)

### Tech Stack used:

- ReactJS for FrontEnd
- NodeJS for API (Backend)
- MySQL as Database. (The SQL database schema is also attached in the repository.

Here are few screenshots of UI where the tools used are ReactJS, NextJS and language of coding is Javascript.

## 1. Login Page

![Screenshot (187)](https://github.com/vatsalpsutariya/Summer_Project/assets/122974525/fb21a197-1f18-489e-876b-018da57fd148)

- Here we can see that is the user credentials don't match with the ones in database, the authentication fails.
- Also used 'context' for session storage

## 2. Client Dashborad

![image](https://github.com/vatsalpsutariya/Summer_Project/assets/122974525/c0c05e5e-2a5a-4274-a07f-a1fb7eea6f52)

- It show the data of how many shipments are there along with the count on the basis of status i.e. Dispatched, Delivered etc.
- It also shows the pie-chart and the bar graph of last year shipments for a visual overview of the shipments.
- The side navigation bar is yet to be filled with different features and functionalities. (open for extension)

![image](https://github.com/vatsalpsutariya/Summer_Project/assets/122974525/26ab0556-ccf9-46b6-8d64-d7412a9ba92e)

- Here it shows the in-depth view for all the shipments and also provides the highlighted status view.
- A Search-Box is provided to search on the basis of load No., carrier name, shipper name, consignee, etc. and it is real time search box it looks for entered value exactly at the time of entry in box.
- We can also filter the data on the basis of status by just clicking on one of the boxes, data will be filtered as shown below.

![image](https://github.com/vatsalpsutariya/Summer_Project/assets/122974525/0fd36411-97e7-44a7-94b7-2a29047be695)

- We also have a button called 'Add Shipment' that redirects us to the next page.

## 3. Add New Shipment

![image](https://github.com/vatsalpsutariya/Summer_Project/assets/122974525/bcbad252-a782-4f73-8baa-29da16e85b27)

- Here we can enter the details of the shipments and all that data forms a json object on clicking 'Proceed'.
- Now this json object is sent to one of the API endpoint and that will add the data to the MySQL database server.

### Along with these, many other functionalities are provided by the backend, check in the repository for available backend modules with business logic functions.

### Moreover the services are also decoupled as modules in backend folder so each service/feature is extensible for future.

Note: This version may have many ways for further optimization and there's also a space for further develpoment, see you soon at in next version.
Have a nice day :)
