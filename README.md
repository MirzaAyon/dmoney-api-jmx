## dmoney-api-jmx

### Requests: 
1. Login to user
2. Create a new agent
3. Give balance to the newly created agent from system
4. Create a customer
5. Search the newly created user by phone number
6. Deposit balance to the customer from the agent
7. Withdraw some money from the agent
8. Delete the user

### How to open the jmx file in the jmeter
1. keep the jmx file and csv files in the been folder
2. open apache-jmeter software
3. open the jmx file

### How to generate report:
1. open bin folder
2. go to cmd
3. give this ```jmeter -n -t [jmx file] -l [results file] -e -o [Path to web report folder]``` command 
4.  report will be generated in the report folder