# RestAPI-Template-Project
- REST API (Representational State Transfer Application Programming Interface) is a type of web service that uses HTTP (Hypertext Transfer Protocol) methods such as GET,   POST, PUT, DELETE, etc., to manipulate resources or data on a server
- OPen designcenter under the anypoint platfrom using your credentioals.
- create new API specification file.
![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/1.png)

- Then you will provide a name that can be unique. 

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/2.png)

- create one file, that contains variable and data types thses are comes under one folder

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/3-folder-creation.png)

- create two folder one folder namely request it conatins put some input requested data and the give it a name.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/request-folder.png)


![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/request-file.png)


- Another folder namely response it conatins put some response  data and give it a name.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/response-folder.png)


![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/response-file.png)

- Add this json schema file while you expected output comes from json format.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/json-schema-file.png)

- Add this RAML file while you request input data is placed here.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/raml-file-creation.png)

- Open dependencies they contains fragments add API specification fragment file using + symbol besides on fragments, before you adding this file create one fragment file and publish into exchange.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/add-common-traits.png)

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/add-common-traits1.png)

- After completed you API development code, apply mockservice using documentation icon placed on the  right side top.

 ![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/open-doc-check-every-url-inmockservice.png)
 
- Check each and individual base path is it working perfectly or not based on your requirements.

 ![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/after-hitting-tryit-200%20ok.png)

- Its working perfectly publish into the exchange.

 ![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/publish-to-exchange.png)
 
 - check the API in Exchange 
 
  ![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/exchange-test.png)
 
- Now open anypoint studio create a new file give it a name, and open exchange under the import a published API they conatins from exchange open it.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/new-app-creation.png)

- Now it shows add dependencies to project here add account using anypoint platform credentials.

- Now add above published project mentioned that application name.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/get-template-from-anypoint%20platform.png)

- Now the application is open in the anypoint studio successfylly.
- Below you see the application main file.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/create-config-implementatio-error-files.png)

- create a config file, implementation file and error handling file by using Mule config option it is available in --> new project creation.

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/using-muleconfig-file-create-config-error-implemenation.png)

- implementation file

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/implementation-flow.png)

- configuration file

![](https://github.com/manikrishna7265/RestAPI-Template-Project/blob/main/global-config.png)



