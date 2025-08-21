# EJ2\-DocumentEditor\-Java\-WebService

This repository provides a working example of how to host a Java\-based web service backend for the Syncfusion Document Editor (a.k.a. Word Processor) component. 

# How to host the DocumentEditor service.

## Maven Project

Please find the list of commands used for running and deploying the spring boot application in Azure.

Clean the package using

> mvn clean package

Run the application locally using

> mvn spring-boot:run

Build the package using

> mvn package

Above package generation command creates the "tomcat-0.0.1-SNAPSHOT.war" in the below location.

> target\tomcat-0.0.1-SNAPSHOT.war

Please create a Azure app service with Java & Tomcat.

After creating the app service 

>Development Tools -> Advanced Tools -> Go -> Debug console -> CMD

Once the file manager is opened please navigate to

>site -> wwwroot -> webapps

Upload the generated war file "tomcat-0.0.1-SNAPSHOT.war" the application will be hosted under

>{site-name}/tomcat-0.0.1-SNAPSHOT
>
# Support and feedback

For any other queries, reach our [Syncfusion® support team](https://support.syncfusion.com/?utm_source=github&utm_medium=listing&utm_campaign=github-github-document-editor-examples) or post the queries through the [community forums](https://www.syncfusion.com/forums?utm_source=github&utm_medium=listing&utm_campaign=github-github-docio-examples). 

Request new feature through [Syncfusion® feedback portal](https://www.syncfusion.com/feedback?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 

# License

This is a commercial product and requires a paid license for possession or use. Syncfusion's licensed software, including this component, is subject to the terms and conditions of [Syncfusion's EULA](https://www.syncfusion.com/license/studio/22.2.5/syncfusion_essential_studio_eula.pdf?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). You can purchase a licnense [here](https://www.syncfusion.com/sales/products?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples) or start a free 30\-day trial [here](https://www.syncfusion.com/account/manage-trials/start-trials?utm_source=github&utm_medium=listing&utm_campaign=github-github-documenteditor-examples). 

