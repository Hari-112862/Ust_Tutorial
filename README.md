StudentDemo


#Requirements : 

 Java 1.8
 mvn 3.5.x or above

#Steps 
 1) Clone this repo 
 2) Run "mvn clean install" 
 3) Run employeeTracker*.jar 
 java -Dspring.profiles.active=local -Duser.timezone=Asia/Kolkata -Dspring.employeeTracker.log.dir={Your_log_path} -jar employeeTracker*.jar 


Swagger Details


 Url: http://localhost:8080/student/swagger-ui.html 
 For all end points ,provide following header values 
 Content-Type :application/json 
 Accept-Language:application/json 