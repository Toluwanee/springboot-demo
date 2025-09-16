# springboot-demo
Setting up a CI/CD pipeline for a basic java app from code to deployment


git clone 


mvn clean package -DskipTests -U

to build the jar file


Ensure you are in the folder where you can see the pom.xml folder when you run 'ls' command. (Do not navigate to the folder)


run  java -jar target/demo-0.0.1-SNAPSHOT.jar (confirm this name in the folder first) 


on your browser, run this; <your IP>:8080


curl http://localhost:8080/
# should print: Hello from Spring Boot!

