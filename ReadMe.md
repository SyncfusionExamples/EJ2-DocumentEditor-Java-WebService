# How to host the DocumentEditor service.

## Add Wordprocessor jar file

`syncfusion-ej2-wordprocessor-18.1.0.29.jar` file available in [Essential-JS2](https://www.syncfusion.com/downloads/essential-js2) build installed location.

**Syntax:**
> Jar file: `(installed location)/Syncfusion/Essential Studio/JavaScript - EJ2/(installed version)/JarFiles/syncfusion-ej2-wordprocessor-(installed version).jar`

**Example:**
> Jar file: `C:/Program Files (x86)/Syncfusion/Essential Studio/JavaScript - EJ2/18.1.0.29/JarFiles/syncfusion-ej2-wordprocessor-18.1.0.29.jar`

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

