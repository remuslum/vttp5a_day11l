# Maven compiler commands
In Project Root folder
./mvnw clean

package the compiled classes into jar file
./mvnw package

Delete target, redownload dependencies, recompile to class files, package to jar/war
./mvnw clean package

Run the application in embedded localhost server
./mvnw spring-boot:run
