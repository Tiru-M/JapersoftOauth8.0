# JapersoftOauth8.0
Jaspersoft Oauth with Okta IDP
Add JRS Jars as User library to your project to compile the code base

#Deploy Instructions

Two Options:
Copy the complied .class files to WEB-INF\classes\ directory
C:\Jaspersoft\JRS80\apache-tomcat\webapps\jasperserver-pro\WEB-INF\classes\com\jaspersoft\jasperserver\ps\OAuth

Export the Jar file and place in 
WEB-INF\lib inside Jaspersoft

and 
applicationContext-externalAuth-oAuth.xml file needs to be placed in the WEB-INF folder

Restart tomcat and access "http://localhost:8080/jasperserver-pro/oauth"
to test the Oauth module


