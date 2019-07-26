## Web Automation for Facebook Using Selenium and TestNG

**_(README EDITING IN PROGRESS)_**

### Summary:

This project is a web automation framework example built using Page Object Model, Selenium, and TestNG. The test cases included cover 3 different scenarios:
1. Successfully logging into an existing Facebook account (correct credentials)
2. Unsuccessfully logging into an existing Facebook account (incorrect credentials) 
3. Creating a new account


### Features:

- Selenium 
- ChromeDriver (Google Chrome browser)
- GeckDriver (Mozilla Firefox browser)
- TestNG
- Test Cases


### Requirements:

- Eclipse IDE
- Java Platform (JDK)
- Java Client JAR
- Selenium Java JAR
- Selenium Server Standalone JAR
- TestNG JAR
- ChromeDrvier JAR
- GeckoDriver JAR
- TestNG Eclipse plugin


### Configuring:

1) **Jave Platform (JDK)** - Download and install the Java Platform JDK for your respective hardware https://www.oracle.com/technetwork/java/javase/downloads/index.html

2) **Eclipse** - Download and install the Eclipse IDE for Java Developers https://www.eclipse.org/downloads/packages/

3) **Java Client JAR** - Download the Java Client JAR file https://mvnrepository.com/artifact/io.appium/java-client/4.1.2

4) **Selenium Java JAR** - Download the Selenium Java JAR file https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java

5) **Selenium Server JAR** - Download the Selenium Server JAR file, **please download the same version number as the Selenium Java JAR downloaded in the previous step**

6) **Chrome & Firefox JARs** Download JAR files for Chrome and Firefox browsers
https://sites.google.com/a/chromium.org/chromedriver/downloads and https://github.com/mozilla/geckodriver/releases

7) **Organize JARs** - Place JAR files in a dedicated folder (preferrably the same location as your workspace folder), this folder will be referenced later when we import the project

8) **Eclipse TestNG Plugin** - In Eclipse, click Help -> Eclipse Marketplace -> search for TestNG -> install "TestNG for Eclipse" -> Confirm

9) **Download Project** - Download the project zip file from this repository and unzip

10) **Import Project** - In Eclipse, click File -> Import -> chose "Existing Projects into Workspace" -> Next -> choose "Select Root Directory" -> Browse -> choose the unzipped project-> Finish

11) **Import JAR Files** - Once the project has been imported, right click the project in the left sidebar -> Build Path -> Configure Build Path -> Add External JARs -> choose all of the JARs downloaded in the previous steps -> Open -> Apply -> OK


### Running Tests:
