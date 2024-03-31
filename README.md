
# demo-transaction-api-jmx

## Technology and Tool Used
- Apache JMeter
- Java

## Requests
1. Admin creates an agent and a customer
2. Deposit 2000 tk to agent from system account (fromAc: SYSTEM)
3. Deposit 1000 tk to customer from agent account
4. Check balance from customer account
5. Withdraw 500 tk from customer account
6. Search the newly created user by email
7. Payment 200 tk from customer account (Merchant account: 01712121212)

## How to run this project
- clone this project
- copy the load_test_b9.jmx file into bin folder of installed location of Jmeter
- open the load_test_b9.jmx file with jemeter & run the project
- to Generate report on the command prompt, delete the already copied .csv file and Report folder from the project
- hit the following command:
- jmeter -n -t .\load_test_b9.jmx -l .\load_test_b9.csv -e -o Report

## Prerequisite
- Jmeter and Java must be installed

## Generated Html Report
![html-report-1](https://github.com/touhid-96/demo-transaction-api-jmeter/assets/29010371/cc89cb96-5efb-4eff-be03-9e83b56aa0db)
![html-report-2](https://github.com/touhid-96/demo-transaction-api-jmeter/assets/29010371/58dabbda-b411-47b4-bd37-68afeca30faa)

## Summary Report
![summery_report](https://github.com/touhid-96/demo-transaction-api-jmeter/assets/29010371/4e536c0c-5b47-404b-988f-6d00a2f84c4c)

## Requests Screenshot:
![http_requests](https://github.com/touhid-96/demo-transaction-api-jmeter/assets/29010371/20bf5f6c-c181-4b0a-bfab-674fcc2bba97)
