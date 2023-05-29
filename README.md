# MuleSoft Engineer Homework Assignment

### Prerequisites
1. Create a new account on [Anypoint Platform](https://anypoint.mulesoft.com/login/)
2. Please ensure that the created account on Anypoint Platform should not have any other project(s).
3. Install the [Anypoint Studio](https://www.mulesoft.com/lp/dl/anypoint-mule-studio) on your system ( if you dont have it already)
4. Have [Open SSL] (https://www.openssl.org/) installed on your system.


### Assignment
## Part 1 : Create and Deploy a REST API
1. Create a new workspace in Anypoint Studio
2. Create an API specfication project in Anypoint Studio named jc-industry-eapi.
3. The API specification should use resourceTypes. 
4. The API specification should use a trait named 'client-id-required' . This trait must be applied on all the end points.  
5. Design the RAML API specification to expose CRUD operation on User object and Customer object. The Object models (user.raml and customer.raml) are attached in this repo.
 - Users
    - GET /users
    - POST /user
    - PATCH /user/{id}
    - DELETE /user/{id}
  - Customers
    - GET /customers
    - POST /customer
    - PATCH /customer/{id}
    - DELETE /customeer/{id}
6. Publish the API specification to Design Centre from Anypoint Studio.
7. Publish the API specification to Anypoint Exchange from Design Centre.
8. Create a new mule project jc-mulesoft-industry-eapi by importing the API specification from Design centre into your workspace. 
9. Deploy the project jc-mulesoft-industry-eapi to Cloudhub.
10. Manage the API jc-industry-eapi in API manager.
11. Apply the client_id enforcement policy on the API jc-industry-eapi.
12. Apply Rate limiting policy on the API (rate limit of three requests every six seconds)
13. Access the exposed API via any REST client (Postman, curl etc)

## Part 2 : Secure the API 
1. As Cloudhub will not allow you to implement 2-WAY TLS, lets try to implement 2-WAY TLS locally.
2. Create 2 self signed certificates via open ssl. 
3. Secure the API via 2-WAY TLS.
