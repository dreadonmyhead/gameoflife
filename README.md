# Game Of Life
Simple Selenium tests for Game Of Life web application

# Preconditions
You need to have java installed in your local PC. Download Java SDK 1.8+
Download any browser driver that you want to use for your test automation. Chrome https://chromedriver.chromium.org/downloads
Download selenum standalone server jar https://www.selenium.dev/downloads/

# Setup
Clone project or download zip. Open it in any IDE. 
Setup project SDK, in IntelliJ File -> Project Structure -> Project -> Project SDK -> select your Java SDK.
Add selenium jar to the libraries File -> Project Structure -> Libraries -> Click plus -> Java -> select selenium jar path
Add JUnit jar from Maven File -> Project Structure -> Libraries -> Click plus -> Maven -> search for "Junit" and select junit 4.0
Put browser driver exe file to the path. In example chrome driver is used.

# Run
Right click on GameOfLifeTestSuite and select green Run icon
