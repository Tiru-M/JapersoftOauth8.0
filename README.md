# JapersoftOauth8.0
Jaspersoft Oauth with Okta IDP
Add JRS Jars as User library to your project to compile the code base

#Deploy Instructions

Two options: 

1)Copy the compiled .class files to WEB-INF\classes\ directory

For instance: 
C:\Jaspersoft\JRS80\apache-tomcat\webapps\jasperserver-pro\WEB-INF\classes\com\jaspersoft\jasperserver\ps\OAuth

Or 

2)Export the Jar file and place in 
WEB-INF\lib inside Jaspersoft

Add: applicationContext-externalAuth-oAuth.xml file needs to be placed in the WEB-INF folder

Update the entries with your OAuth provider information.

Restart tomcat and access "http://{JRShostname}:{portnumber}/jasperserver-pro/oauth" to test the Oauth module


