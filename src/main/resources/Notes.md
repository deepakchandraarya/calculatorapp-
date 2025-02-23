## Git Commands to Push Code to a New Repository
To build and run the project using Maven, use the following commands:

1. Clean and package the project:
    ```sh
    mvn clean package
    ```

2. Run the Spring Boot application:
    ```sh
    mvn spring-boot:run
    ```

3. Run the packaged JAR file:
    ```sh
    java -jar target/your-app-name.jar
    ```

1. Add a remote repository:
    ```sh
    git remote add origin https://github.com/deepakchandraarya/calculatorapp-.git
    ```

2. Rename the current branch to `main`:
    ```sh
    git branch -M main
    ```
    4. Check the status of your repository:
        ```sh
        git status
        ```

    5. Commit your changes:
        ```sh
        git commit -m "Initial commit"
        ```
3. Push the code to the remote repository:
    ```sh
    git push -u origin main
    ```
    ## Git Commands to Push Code to a New Repository
To build and run the project using Maven, use the following commands:

1. Clean and package the project:
    ```sh
    mvn clean package
    ```

2. Run the Spring Boot application:
    ```sh
    mvn spring-boot:run
    ```

3. Run the packaged JAR file:
    ```sh
    java -jar target/your-app-name.jar
    ```

1. Add a remote repository:
    ```sh
    git remote add origin https://github.com/deepakchandraarya/calculatorapp-.git
    ```

2. Rename the current branch to `main`:
    ```sh
    git branch -M main
    ```

3. Push the code to the remote repository:
    ```sh
    git push -u origin main
    ```