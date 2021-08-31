# FlexiBook Desktop Application

Completed as a course project of ECSE 223 (Model-based Programming) in Fall 2020, FlexiBook application is for micro-enterprises (i.e., one-person businesses such as hairdressers or physiotherapists) that first allows various services and service combos to be specified and then supports the owner of the business in the appointment booking process. In our implementation, we focused especially on barber shops.

## Project Demo

Below are a few figures of how our application functions for both customers and barber shop owners. 

User login
![de1](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de1.PNG)

Shop owner picking services and combos
![de2](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de2.PNG)

Shop owner managing business information
![de6](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de6.PNG)

Shop owner managing reservation on a calendar
![de7](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de7.PNG)

Customer making a reservation
![de4](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de4.PNG)
![de3](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de3.PNG)

Customer managing account information
![de5](https://github.com/AntoineWY/FlexiBook-Desktop-Application/blob/main/223%20demo/de5.PNG)

## Environment

The preferred environment is **Eclipse** with Java version above 12. This project uses standard java programming for backend logics, **java-swing** for front view design, and **cucumber** to facilitate testing user stories.

Below lists a set of dependencies which the program requires.

```gradle
dependencies {
    // This dependency is used by the application.
    implementation 'com.google.guava:guava:29.0-jre'

	// custom date picker library
	implementation 'org.jdatepicker:jdatepicker:1.3.4'
    
    // cucumber.io dependencies
    testImplementation "io.cucumber:cucumber-java:6.6.0"
    testImplementation "io.cucumber:cucumber-junit:6.6.0"

    // Use JUnit Jupiter API for testing.
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.6.2'

    // Use JUnit Jupiter Engine for testing.
    testRuntimeOnly 'org.junit.jupiter:junit-jupiter-engine:5.6.2'
    
    // This is here to solve Eclipse IDE Junit 5 compatibility issues
    testRuntimeOnly 'org.junit.vintage:junit-vintage-engine:5.6.2'
    
    testRuntimeOnly "org.junit.platform:junit-platform-commons:1.7.0"
}
```

## Link to Original Project Repo
[https://github.com/F2020-ECSE223/ecse223-group-project-p14/wiki](https://github.com/F2020-ECSE223/ecse223-group-project-p14/wiki)

