# Dmoney Assignment by Jmeter

## Project Summary:
This project has automate user API from Jmeter 

## Technology Used
Apache JMeter
Java

## Scenario
Add following requests:
•	Admin creates an agent and a customer
•	Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
•	Deposit 1000 tk to customer from agent account
•	Check balance from customer account
•	Withdraw 500 tk from customer account
•	Payment 200 tk from customer account (Merchant account:	01686606905)
•	Assert expected customer balance


## How to run this project
•	Clone this project
•	Save the dmoney-assignment.jmx file into bin folder of installed location of Jmeter
•	Open the dmoney-assignment.jmx file with jemeter & run the project
•	To Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
•	Hit the command for html report:
  $ jmeter -n -t dmoney-assignment.jmx -l dmoney-assignment.csv -e -o Reports


## Report

https://drive.google.com/file/d/1fjjGd8G-aJL9d5JERaM9h0tpbVXWX_IS/view?usp=sharing



## User documentation:
Will get the user API URL, endpoint, header info and demo data from here:
https://documenter.getpostman.com/view/1844288/UzBiQpVN

## Transaction documentation:
Will get the transaction API URL, endpoint, header info and demo data from here:
https://documenter.getpostman.com/view/1844288/2s7YmzAhnk



