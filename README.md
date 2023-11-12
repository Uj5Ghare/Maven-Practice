# Maven-Practice
This is a simple Maven Project which `compile`,`build` & `compress` code into `".jar"` file

## Requirements
1. `Openjdk-17-jre`
   ```
   yum install java-17 (Amazon Linux/fedora/CentOS)
   apt install openjdk-17-jre (Ubuntu/Debian)
   ```
   
2. `Maven`
   ```
   yum install maven (Amazon Linux/fedora/CentOS)
   apt install maven (Ubuntu/Debian)
   ```
   

## Installation
1. Clone the repository
   ```
   git clone https://github.com/Ujwal-s-Projects/Maven-Practice
   ```

2. Enter into main directory
   ```
   cd Maven-Practice/
   ```
   
3. Build the application 
   ```
   mvn clean install 
   ```

4. Run the application
   ```
   java -jar target/my-todo-app-1.0-SNAPSHOT.jar 
   ```

