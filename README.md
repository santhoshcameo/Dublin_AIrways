# Dublin_AIrways

The Application is developed using Java/J2EE/JSP technologies 
Spring used as framework, and Maven used as build tool.

Its developed as part of college project using RESTful API services.

Modules
1. Login Module
2. Admin Module
3. User Registration
4. Flight booking
5. Food booking
6. Map and Weather
7. Feed Back module
Registration Module:
The interface for users to register with Dublin Airways. The registered users can book flight tickets. The details are stored in amazon web services RDS.
Login Module:
Interface for users to login to the application, also the application provides users to login using google credentials.
Flight booking:
The module used to book the flight. The users can choose the destination and source along with time and date to complete the registration. The Flight booking is working based on API consuming. We have consumed a API and sending the parameters array of JSON and book the flight. The details are stores in third party data base.
Food Booking
The module is developed as a concept of API, and anyone who need to book food service they can consume this API. The request and response formats are based on JSON format and unique boking ID.
Google Map and Weather.
The API google map is consumed as third party to point the users about flight services. The users can track them using google map.
The weather gadget is added to application since users can forecast the weather prior to their ticket booking. The forecasted gadget can
give 5-day weather forecast of Dublin Airways
flying destinations.
Technical Specifications:
Programming
Language
Java
Front end J2EE/JSP
Scripting jQuery and Java
Script
Framework Spring
Build Tool Maven
Cloud Vendor Amazon Web
Services
Database AWS RDS
Deployment Tools Elastic beanstalk,
EC2
Web Server Tomcat 8.5
The application is developed using Spring
framework and Maven as build tool.
Application is deployed in AWS EC2 t2.micro
instance and deployed in Tomcat web server.
Security groups are added as part of the web
application hosted in EC2 instances.
API Development:
As part of this application development a sub
project is developed and that also hosted on
AWS cloud platform on the same EC2
instances. The databases are connected to the
same databased on AWS RDS.
The API performs the booking of the
food items. It’s a generic design who ever
consumes can change the food items and its
prices. Also, API provides the developers to
choose the date and time to book the flight. The
API contains dish type and dish size like small,
medium and large.
