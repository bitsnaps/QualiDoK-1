# QualiDoK

QualiDoK is web app uses a REST API as a layer on top of LogicalDOC Community Edition with additional features (Multi-Server, OCR...).

# Run
You can run the app using Gradle:
```bash
gradle run
```

# Build a runnable jar
You can build a runnable jar with all dependencies using gradle's shadowJar plugin:
```
gradle shadowJar
java -jar build/libs/QualiDoK-all.jar
```