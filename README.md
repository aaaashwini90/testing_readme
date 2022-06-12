
# Inside UCL E2E Automation

This repository contains a collection of Regression Test Suite in BDD + TDD framework for Inside UCL application




## Features:

This project is used by the following companies:

- Crisp & Clear maven folder structures
- Extensive methods in CucumberRunner class
- CucumberOptions with detailed explanation of using "tags", "glue" ,”monochrome” , “pulgins”
- Screenshots on failure feature in CucumberRunner class
- TestNG Annotations/hooks like "@After", “@Before” etc.
- Descriptive pom.xml and testng.xml
- Scenarios for Regression suite features and step definition files
- Methods for running tests in Firefox and Chrome and Edge browsers


## Installation (pre-requisites)

1. JDK 1.8+ (make sure Java class path is set in environment variables)
2. Maven (make sure .m2 class path is set in environment variables)
3. Eclipse
4. Eclipse Plugins for
   - Maven
   - Cucumber
   - TestNG
5. Browser driver (make sure you have your desired browser driver and class path is set)

# Maven folder structures 

    
## Maven folder structures 


![alt text](https://github.com/aaaashwini90/testing_readme/blob/main/SS1.png)



## Documentation

[Documentation](https://linktodocumentation)


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Directory layout Files

1. src/main/java 

Inside this folder you can put all the application resource files. Resources for the main (real) artifact should be put in this folder.
In this folder , you will find Utilities package. In this package , we are having common generic java classes like- cucumberLogs.java and cucumberReport
Were cucumberLogs file is to generate the application logs file which have a specified format.
And cucumberReports file is to generate cucumber Reports after script Execution.

2. src/test/java 
Inside this folder you can put all the application test resource files. Resources for the test artifact should be put in this folder.
In this folder, you will find 2 packages as below-
i. StepDefinitions- Here we have step definition classes. As below