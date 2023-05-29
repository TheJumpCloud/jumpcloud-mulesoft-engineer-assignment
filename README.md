# MuleSoft Engineer Homework Assignment

### Prerequisites
1. Create a new account on [Anypoint Platform](https://anypoint.mulesoft.com/login/)
2. Please ensure that the created account on Anypoint platform not have any other project.
3. Install the [Anypoint Studio](https://www.mulesoft.com/lp/dl/anypoint-mule-studio) on your system ( if you dont have it already)
4. Have [Open SSL] (https://www.openssl.org/) installed on your system.


### Assignment
## Part 1 : Create and Deploy an API
1. Create a new workspace in Anypoint Studio
2. Create an API specfication project in Anypoint Studio named jc-users-eapi.
3. The API specification should use resourceTypes and traits for client_id enforcement policy. 
4. Design the RAML API specification to expose CRUD operation on User object . The User Object model (user.raml) is attached in this repo.
    - GET /users
    - POST /user
    - PATCH /user/{id}
    - DELETE /user/{id}
5. Publish the API specification to Design Centre.
6. Publish the API specification to Anypoint Exchange.
7. Create a new mule project jc-mulesoft-users-eapi by importing The API specification from Design centre into your workspace. 
8. Deploy the project jc-mulesoft-users-eapi to Cloudhub.
9. Manage the API jc-users-eapi in API manager.
10. Apply the client_id enforcement policy on the API jc-users-eapi.
11. Access the exposed API via any REST client.

## Part 2 : Secure the API 
1. Create 2 self signed certificates via open ssl. 
2. Secure the API via 2-WAY TLS.
3. Since Cloudhub will not allow you to implement 2-WAY TLS, lets try to implement 2-WAY TLS locally.
