# EI_FileConnectorDemo


This setup demonstrates
- Folder search, File transfer and Send Notification capabilities of WSO2 Enterprise Integrator.

# Versions
- v1.0.0 using WSO2 EI 6.5.0, File connector 2.0.18, Amazon Simple Notification connector 1.0.1

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

- Download and Install WSO2 ESB File Connector and WSO2 Amazon SNS Connector from WSO2 connector store
WSO2 Connector store URL : https://store.wso2.com/store/assets/esbconnector/list
WSO2 ESB File connector URL : https://store.wso2.com/store/assets/esbconnector/details/5d6de1a4-1fa7-434e-863f-95c8533d3df2
WSO2 ESB Amazon SNS Connector URL : https://store.wso2.com/store/assets/esbconnector/details/20672bcc-fcd4-41a8-89db-3458d5790162

- Now install above connectors to WSO2 Integration Studio and WSO2 Enterprise Integrator
For instructions refer below links
https://docs.wso2.com/display/ESB500/Working+with+Connectors+via+the+Management+Console
https://docs.wso2.com/display/ESB500/Working+with+Connectors+via+WSO2+ESB+Tooling

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
