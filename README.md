# easyjspforum
Easy JSP Forum is a community forum developed with JSP technology of all features of a standard web-based forum. It is easy to deploy on any web container such as Tomcat and can be integrated with any SQL database system.

Installation instructions:

For testing purpose the project is currently written to support Microsoft Access.
More database support will be available soon as the project is being developed.

To successfully install Easy JSP Forum on your machine follow these easy steps, if you 
already have JDK 1.4 and Tomcat 5.5 installed on your machine you can skip steps 1 - 3

In the following steps the following will be used for illustation purpose:

JDK folder: C:\j2sdk1.4.2_12
Tomcat folder: C:\jakarta-tomcat-5.0.28
Tomcat port number: 8080

Your actual configurations may be different depending on the versions used.

1. Download and install Java Development Kit 1.4 (JDK) available at http://java.sun.com

2. Download and install Jakarta Tomcat 5.5 available at http://tomcat.apache.org

3. Setting the environment variables in your machine as follows:
   JAVA_HOME = C:\j2sdk1.4.2_12
   CATALINA_HOME = C:\jakarta-tomcat-5.0.28

4. Unzip file forum.zip into a folder forum and copy this folder to the
   folder webapps of Tomcat (e.g: C:\jakarta-tomcat-5.0.28\webapps\forum)

5. Setup the database for the project: please follow these steps:

   5.1 Go to Control Panel -> Administrative Tools -> Data Sources (ODBC)
   5.2 Click on the System DSN tab of the ODBC dialog box
   5.3 Click Add -> select Microsoft Access Driver (*.mdb) -> click Finish
   5.4 Enter Forum in Data Source Name and enter Forum database in Description
   5.5 Click Select... and locate the database file (Forum.mdb) in the database 
       folder (e.g: C:\jakarta-tomcat-5.0.28\webapps\forum\database\Forum.mdb)
   5.6 Click OK -> Click OK -> Click OK to close ODBC dialog box

6. Startup Tomcat by running the file C:\jakarta-tomcat-5.0.28\bin\startup.bat

7. Open web browser and enter the address: http://localhost:8080/forum to start

8. Test the project with 3 default accounts as follows:
   Administrator: username: admin  password: admin
   Moderator: username: mod  password: mod
   Member: username: member  password: member


Any comments or suggestion please email me at dacthongvu@gmail.com

Thank you for your support.

Thong.
