# How to run the Test #

**Prerequisite**
1. Java environment
2. Maven



**Note: Crossbrowser testing.**


- Configure webdriver.
    - download ChromeDriver from [http://chromedriver.chromium.org/downloads](http://chromedriver.chromium.org/downloads).
    - Copy your downloaded **chromedriver.exe** and  **geckodriver.exe**  file path.

    

Project is ready to run. Execute following commands and enjoy the automatic web-driver test.
- Go to project path in terminal. For example: C:\Users\User-Name\eclipse-workspace\E2EUserJourney>
- Run `mvn clean`
- Run `mvn compile`
- Run `mvn test`

You can find the test result in `E2EUserJourney\target\surefire-reports\Test01.html`.