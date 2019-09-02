# devops
Sample Java Apps

Pre-requisits: - 
  MySQL is up and running.

Dependecies 
  1) MySQL - Mysql config is done in spring-servlet.xml. Current config in code is 
    <property name="url"
			value="jdbc:mysql://localhost:3306/test"></property>
		<property name="username" value="root"></property>
		<property name="password" value="root"></property>
  2) Maven
  3) Java  ( JDK 1.8 )
  4) Tomcat ( any latest version )
  
  Commands: - 
     To build application : mvn clean package
     Then deploy the war file created from step 1 into Tomcat "wabapps" folder.
     Restart the Tomcat.
     Access application at http://localhost:8080/SpringMVCPagination/viewemp
     
