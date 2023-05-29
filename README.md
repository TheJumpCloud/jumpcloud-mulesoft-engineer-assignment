# MuleSoft Engineer Homework Assignment

## Part 1: Database Queries

### Prerequisites
1. Have an account on [Anypoint Platform](https://anypoint.mulesoft.com/login/)
2. Install the [Anypoint Studio](https://www.mulesoft.com/lp/dl/anypoint-mule-studio) on your system ( if you dont have it already)


### Assignment
1. Create and provide a script with logging to achieve each of the following:
  - We’re coming out with a new hoppy delicious IPA. To let our customers know, we need two mailing lists.
    - One that includes the email addresses of all of our customers
    - Another that includes only the email addresses for customers whose favorite beer is an IPA.
  - We need to gather some data on our tap rooms to show which is the most popular location. We need to know how many customers have frequented each location between 1/1/2021 - 4/1/2021.
  - We’re trying to determine what type of beer is most popular with our customers so we can determine what our next experimental beer should be! Can you provide us with an array of objects that include the beer name, type, and number of customers where that beer is their favorite?
2. Provide the output results for each of these requests.

## Part 2: Interacting with JumpCloud

### Prerequisites
1. Create a free JumpCloud Organization: https://console.jumpcloud.com/signup
2. Install the JumpCloud Agent on a system (Mac, Windows, or Linux)

### Assignment
1. Using the programming language of your choice (Go or JavaScript preferred), complete the following and provide your solution for each:
   - Create and activate 2 Users
   - Create a Group of Users
   - Associate Users to the Group of Users
   - Associate one User to the recently added system in JumpCloud

2. Log in to the system as the JumpCloud managed user

3. Set agent logs to DEBUG on system and provide a copy of agent logs

4. Add a SSO (SAML) Connector in the JumpCloud Admin Console  
*Note: You may choose the web-based application of your choice but many applications/services provide free trials and will allow enabling of SAML authentication. For example: Salesforce (Trailhead) or ThousandEyes allow for SAML configurations with free trial accounts.*. 
   - Configure the SAML authentication on the chosen app/service-side
   - Validate one of your users created in Task 1 can login to the application through the user’s JumpCloud portal
   - Create and provide a HAR file of the SAML request
