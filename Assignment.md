
# Assignment 1

## Problem Definition

In order to satisfy the increasing demand for better customer satisfaction and retention on the phone, the Travel Company decided to implement a new system in its Call Management Center (CMC) and integrate it with a new Customer Relationship Management (CRM) platform to handle and support the influx of inbound and outbound callers, as well as to satisfy the demands of the internal team to effectively communicate with customers.

In order to implement a new system, a problem needs to be addressed in order for the new system to address the problem and attempt to fix it. The travel company would want the system to include a function that could adjust the call flow rate to speed up customer calls. Additionally, from the RM's perspective, the system should match customers according to their skills, customer profile and product knowledge. This could improve the call flow rate and may lead to more satisfied customers.

The second issue to be addressed is storage. The new system would need access to the customer database and transaction history. Since the new integrated system is planned to include features that can automatically find the user profile based on their phone number or manually by searching their name, this can check whether the customer is new or returning customer so that we can serve them better. From the perspective of the RM, this will benefit them since they can see the customer purchase history. Additionally, the new CRM should work seamlessly with the news over the phone purchasing system, in-store purchase or online purchase that the customer profile can dynamically update so the phone operator will always have the up to date version of the customer profile. Since the new system will combine a lot of data from the existing IS system, it would be a future proof system that can be used as a hub for automated advertisement or recommendation.

In summary, the core problem the travel company is facing is the slow rate of call flow as a result of customers getting matched with any RM regardless of the RM's knowledge of the product. 

## Stakeholders

* Travel Company Board of Directors
* Travel Company CEO
* Travel Company Relationship Managers
* Travel Company Employees (Employees are employees of the company before they become RMs)
* Customers

## Empathy Maps & POV Statements

### CEO: ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/Samer-EmpathyMaps/IMG/CEO%20Empathy.PNG 'CEO Empathy Map')

The CEO needs to increase the flow of CMC operations because he is then able to help the travel company and this branch expand and grow in the long term.

The CEO needs to see and gauge each RM's number of sales because that will help him in keeping and hiring the good RMs to keep the company's reputation and increase call flow and sales.

### Relationship Managers: ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/Samer-EmpathyMaps/IMG/RM%20Empathy.PNG 'RM Empathy Map')

RMs need to communicate with customers similar to their profile because it is easier to recommend and sell products that the user is familiar with as opposed to selling products that might be out of their knowledge boundaries.

RMs need to call customers who might be interested in the product offering that the RMs offer because they do not want to call a customer and advertise a product that may not interest the customer, potentially losing out on a sale

RMs need to see customer profiles because it is easier to help the customer make an appropriate purchase if the RM is able to know the customer's needs and wants.

### Employee: ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/Samer-EmpathyMaps/IMG/Employee%20Empathy.PNG 'Employee Empathy Map')

Employees need to have their profile built correctly because this will allow them to know which holiday packages they are able to advertise about and which customers to contact or recieve calls from so that they service customers appropriately.

Employees need to answer the questionnaire because this will allow employees to be assigned to holiday packages that they are familiar with and can provide extra details and insights to customers looking to travel to that location.

### Customer: ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/Samer-EmpathyMaps/IMG/Customer%20Empathy.PNG 'Customer Empathy Map')

Customers need to be connected with an appropriate RM because this will allow the customers to make an informed decision on the holiday package and purchase the package satisfactorily.

Customers need to easily get paired up with an RM because customers want to be able to quickly make the call and purchase their package without too much time wasted as they have other business to deal with in their daily lives.

Customers with a long wait time need to be serviced first because they have been waiting for a long time and will slowly get frustrated until they eventually get frustrated and close the call, not making any purchases.

### Board of Directors: ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/JKalair-patch-1-Empathy-Map-BOD/empathy%20map%20board%20of%20directors.PNG 'Customer Empathy Map')

The board of directors need to see positive reception from customers about the new service because this will allow them to articulate if the system is doing well and if it should be kept or adjusted to suit the customer's needs.

The board of directors need to see a positive influence on Relationship Managers because this will allow the board to identify if their RMs are happy with how the system is functioning.

## Objectives

* Create new in-house Customer Relationship Manager (CRM) system with existing features and new features including but not limited to:
  * Improve operation of in-house Call Management Center (CMC)
  * Improve profiling of customers
  * Assign RMs to products they are knowledgeable in 
  * Match Customers with appropriate RMs
* Help Relationship Managers sell holiday packages to customers
* Create a satisfying customer experience over the phone

Acheiving the previous objectives will result in the ultimate goal of increasing the flow of calls in the CMC.

## Design Thinking Approach

![Design Thinking Header](https://public-media.interaction-design.org/images/ux-daily/58089e358c6d5.jpg)

## Reflection - HMWs and Project Assumptions

### HMW Statements

* HMW ensure RM profiles and skills are kept up to date?

* HMW ensure that automatic outbound marketing/selling calls are not excessive?

* HMW ensure customer satisfaction is achieved?

* HMW ensure that the system works effectively?

* HMW automatically route calls to the relevant RMs?

* HMW organise customer profiles so RMs can see relevant information, e.g. needs and wants

* HMW better connect customers with appropriate RMSs?

* HMW add new customer information into the database?

* HMW connect Customers to an appropriate RM?

* HMW speed up the process of connecting to an RM?

* HMW make the wait time for the customers enjoyable or productive?

* How might we design the system so it could build employee's profile which could potentially assist them in matching right customers according to their needs.

* How might we impliment questionnaire that could assist them in assigning them with right holiday packages which they have knowledge of


### Assumptions

* System can access customer's database and transaction history from another department 

* System can automatically find customer's profile according to thier phone number

* Appropriate budget and project time is available

* All approvals have been received to progress with the project

* The CMC system is able to route calls to the next most relevant RM if the initial RM is unavailable, e.g. on another call

* We assume customers consent to receive marketing/promotional calls

* The system has a way of handling customers with the same Customer score

* Employees are the stakeholders taking the Questionnaire before becoming Relationship managers

* The target list contains multiple products proposed to the same customer

## Use Cases:
* System would ask meaningful questionnaire to employee about the company's holiday packages as well as the employee's age, sex, culture and language proficiency. Through the responses the profiler tool woll lodge these details and will be able to detect which is the right product that employee have knowledge of and assign that product or products to the RM

* The board of director also request that the system performance report (both technical and financial) to be made available to all member of the board of director at any time to justify the system. 

* The CEO regularly checks with RM managers who provide data to ensure that the system is working as intended so that the business can generate greater customer satisfaction and profits. 

* Once the RM has made a call, the system will display the necessary customer information alongside a preplanned script catered for the sales pitch. The system will respond with information about the customers past purchases, preferences and possible future plans. The system will allow the RM to input any additional customer information so that future calls can be sorted even more effectively.

* Customer dials the CMC number, which then routes customers to an appropriate RM based on their customer profile and customer score. If it takes too long to connect, the customer connects to the Automated Voice Response (AVR). AVR asks customer about nature of package and the customer answers. The AVR then routes customers to closest available RM. If two customers have the same customer score, customers who have waited longer are prioritized.

## Use Case Diagrams

## Activity Diagrams - JK

## Class Diagrams ![alt text](https://raw.githubusercontent.com/SirDickensBottomskew/ISDMProject/master/IMG/class_diagram_updated.jpg 'Class Diagram')

## Collaborative Diagrams

## Competitive Advantages

* Centralised in house call handling

* Integrates well with software being developed

* Allows for better data collection and analysis

* Reduced long term costs

* Automated caller authentication

* Improved call quality
