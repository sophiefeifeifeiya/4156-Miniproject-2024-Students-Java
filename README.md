# 4156 project 1
## Static Analysis
I am using PMD

### How to run PMD

```
mvn pmd:check
```

Analysis results in the `target/pmd.xml` file

## How to check style
```
mvn spring-boot:run -Dspring-boot.run.arguments="setup"
mvn checkstyle:check
```
## How to run tests
```
mvn spring-boot:run -Dspring-boot.run.arguments="setup"
mvn clean test jacoco:report
```
Test results in the `target/site/jacoco`