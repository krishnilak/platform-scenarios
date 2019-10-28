# PaymentProcess

This setup demonstrates 
- Message routing capabilities of WSO2 Enterprise Integrator. 

# Versions
- v1.0.0 using WSO2 EI 6.5.0

# How to run

- Install WSO2 Enterprise Integrator in your machine, or else download the binary
Download link : https://wso2.com/enterprise-integrator/6.5.0

- Run the WSO2 Enterprise Integrator in integrator profile.
If you are using binary pack, run the executable file under 
<extracted EI pack location>/WSO2EI6.5.0/bin
by executing following command
./integrator.sh

- Download and Install WSO2 Integration Studio 
Download link : https://wso2.com/integration/integration-studio/

- Now import above git repository to your Integration studio workspace

- Create a Composite application by 
New > Composite Application Project > Next > 
tick the checkbox near your ESB solution project and finish

- Build the project by executing 
Project > Build project

- Right click on your Composite application project and click on 
Export Composite Application Project

- Go to your management console, 
https://<host_name>:9443+<port_offset>/carbon/
ex. https://localhost:9443/carbon/

- Go to Main> Manage > Carbon Applications > Add 
upload your expoted .car file and Refersh page after few seconds.
Now your carbon application will be listed under 
Main > Manage > Carbon Applications >List

- Go to Main> Manage> Service Bus> APIs
Now your APIs are ready for use. You can see API information from there


# Setup
![alt text](https://github.com/krishnilak/paymentProcess/blob/master/1.png)
