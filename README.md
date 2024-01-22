This project is a simple "Hellow world" running in java 1.8

You can clone the project using: `git clone https://github.com/catadetest/gs-spring-boot.git`

Build the project using linux environment:
```bash
cd gs-spring-boot/app
mvn -B -DskipTests clean package
mvn spring-boot:run
```

The `mvn -B -DskipTests clean package` command will clear the `target` directory if existed, builds the project and skip test during the build. Finally, the `mvn spring-boot:run` command will run the project on the default port.

By default, your application will be served to port 8080. Navigate to `http://127.0.0.1:8080` in order to review the JSON response.


