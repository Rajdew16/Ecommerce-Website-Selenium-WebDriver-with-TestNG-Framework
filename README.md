
# Ecommerce-Website-Selenium-WebDriver-with-TestNG-Framework

Project is based on Selenium Web Automation, i have used TestNG Framework and provided various tags into test cases.


## Run Locally

Clone the project

```bash
  git clone https://github.com/Rajdew16/Ecommerce-Website-Selenium-WebDriver-with-TestNG-Framework.git
```

-> Open project in Eclipse IDE  
-> Go to testSuites  
-> Select any xml file  
-> Right click -> run as -> TestNG Suite


## Running Project Using Command Line

Open terminal at project level/path  
To run tests, run the following command

```bash
  mvn test
```

## Running Project In Preferred Browser

Open terminal at project level/path  
To run tests, run the following command

For chrome browser  
```bash
  mvn test -Dbrowser=chrome
```
For firefox browser  
```bash
  mvn test -Dbrowser=firefox
```
For edge browser  
```bash
  mvn test -Dbrowser=edge
```
## Report

After executions of test cases you will see a new folder created by name reports under that you will find actual reports of test cases,  

-> reports/index.html
