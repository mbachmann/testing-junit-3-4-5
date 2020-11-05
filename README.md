# Example for Junit Tests

The example code shows a maven project with junit tests in version 3, 4 and 5.

## Running the tests from an IDE
In order to run the tests use eclipse (run as junit test) or intellij (run). 
You can use the maven wrapper to run the tests from the console:

## Running the tests from the console

You can use your installed maven or the project maven wrapper:

Windows: 

```
mvnw test
```

MacOs or Linux

```
./mvnw test
```


## Build the project site with the site plugin

You can build the the project site from this test project with the command:

Windows: 

```
mvnw site:site
```

MacOs or Linux

```
./mvnw site:site
```

The site is built in the project target folder with the name site. You can open the index.html in your browser. If the folder
is not visible in your IDE you can use refresh function from the IDE context menu.
