# Module 19 Challenge: Krypto Jobs

## Introduction
The purpose of this assignment was to create a web based application that would pay a selected employee a specific wage depending on the number of hours said employee worked. The user would choose an employee, see the wage that they charge per hour, and choose how many hours they would like the employee to work. Once the number of hours is set, the user can send ethereum to the employee's crypto wallet as per their entitlement. This would generate a hash that can also be reviewed in Ganache.

## Results
For this challenge I chose to employ Lane. She charged 0.2 ETH per hour. I employed her for 35 hours, which meant I would owe her 7 ETH. 

![image](app_transaction.png)

My crypto wallet in Ganache initially contained 100 ETH. After sending the ETH to Lane's account, you can see that the amount of ETH in my wallet is now 93. 

![image](ganache.png)

By sending the tokens to Lane, it also generated a hash, which can be reviewed below.

![image](ganache_transaction.png)