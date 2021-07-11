# Code Screen Project - Fibonacci Sequence 

This repo is a scoped application build in ServiceNow and linked to github account. Upon installing this repo you will be able to install the complete application in your ServiceNow instance and start using the benefits offered by this application.

# About Project:
## Build an API using Scipted Rest API to generate a Fibonacci number.

### What is Fibonacci?
The Fibonacci sequence begins with the numbers 0 and 1. The third number in the sequence is the first two numbers added together (0 + 1 = 1). The fourth number in the sequence is the second and third numbers added together (1 + 1 = 2). Each successive number is the addition (the sum) of the previous two numbers in the sequence. The sequence ends up looking like this:

0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, and so on and so forth.


## How to install/import this app in ServiceNow
1. Fork the repo by clicking on form and copy the https url as shown below

![fork](https://user-images.githubusercontent.com/87241330/125196429-8ed15080-e277-11eb-8a54-7a65dea05cef.png)

2. Navigate to **System Applications > Studio.**
3. Click **Import from Source Control**


   Studio displays the Import from Source Control fields.
![import](https://user-images.githubusercontent.com/87241330/125196763-a3faaf00-e278-11eb-9a33-c5c3f6a0922f.png)
4. [Click here to know more on how to importing a github file in servicenow.](https://docs.servicenow.com/bundle/paris-application-development/page/build/applications/task/t_ImportAppFromSourceControl.html)
5. Once successfully installed, update sets will be automatically commited in your ServiceNow instance.


## How to use / how to navigate ?
1. Navigate to **Self-Service > Fibonacci Sequence** 
2. Its open's a portal page where you enter the number and submit to view the result.
![Portal](https://user-images.githubusercontent.com/87241330/125197109-0ef8b580-e27a-11eb-9f4d-bf91af4f3312.png)

## User Stories
1. A User can enter **positive number** and hit Submit button - that returns a postive result
2. A User can enter **negative number** and hit Submit button - that returns a error statement

## ATF - Automated Test framework (Test and Test Steps)
   Application offer's ATF (Automated Test Framework). It has four Tests written two positive and two negative. 
   **(Open the test and click on Run Test. System will open a Test client runner run based on the Test steps written and goto Test results to view the results also screenshots will be attached.)** 
   
- Fibonacci page - Positive 
- Fibonacci page - Negative
- Fibonaaci API - Positive
- Fibonaaci API - Negative
    
 #### How to run the ATF Test's
1. Navigate to Automated Test Framework > Tests and search for Fibonacci in the Name field
![image](https://user-images.githubusercontent.com/87241330/125198760-dc9e8680-e280-11eb-8706-19b6a8afbc4d.png)

2. Open the Test and click on Run Test. **Make sure Enable Test / Test suite execution property is enabled**
![image](https://user-images.githubusercontent.com/87241330/125199069-2f2c7280-e282-11eb-83c4-bb299ed7cf35.png)

3. Test runs based on the Test steps and give you the results as shown below.

- **Client Test Runner**
![image](https://user-images.githubusercontent.com/87241330/125199186-a95cf700-e282-11eb-992a-00cc0c972a6c.png)

- **Test Results**
![image](https://user-images.githubusercontent.com/87241330/125199219-cdb8d380-e282-11eb-9f2b-be85c93fc2ff.png)

- **Open the attachments of all the test stpes**
![image](https://user-images.githubusercontent.com/87241330/125199277-15d7f600-e283-11eb-821d-f7008df2a497.png)

- **Step Results**
![image](https://user-images.githubusercontent.com/87241330/125199298-33a55b00-e283-11eb-811e-23f10e15cf74.png)


## Features
- Fibonacci Application is a build-in Public API, any user can use this without an account in ServiceNow
  - [Fibonacci Sequence open source](https://dev73775.service-now.com/fibseq)
- Any thrid party tool can use this api to retun the fibonacci sequence number
	- [Positive result](https://dev73775.service-now.com/api/x_90235_fib/fibonacci_sequence/10) **Enter the postive integer number in the url**
	- [Negative result](https://dev73775.service-now.com/api/x_90235_fib/fibonacci_sequence/-1) **Enter the negative integer number in the url**
  - API accepts both JSON, XML request OR response

## Dependencies
- Make ServiceNow Version is Paris or newer release. (May see inconsistencies in older versions)


