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
3. The API specification should use resourceTypes 
4. The API specification should use a trait named '''client-id-required''' . 
5. Design the RAML API specification to expose CRUD operation on User object . The User Object model (user.raml) is attached in this repo.
    - GET /users
    - POST /user
    - PATCH /user/{id}
    - DELETE /user/{id}
6. Publish the API specification to Design Centre.
7. Publish the API specification to Anypoint Exchange.
8. Create a new mule project jc-mulesoft-users-eapi by importing the API specification from Design centre into your workspace. 
9. Deploy the project jc-mulesoft-users-eapi to Cloudhub.
10. Manage the API jc-users-eapi in API manager.
11. Apply the client_id enforcement policy on the API jc-users-eapi.
12. Access the exposed API via any REST client.

## Part 2 : Secure the API 
1. Create 2 self signed certificates via open ssl. 
2. Secure the API via 2-WAY TLS.
3. Since Cloudhub will not allow you to implement 2-WAY TLS, lets try to implement 2-WAY TLS locally.
