

# App Automation on EMI calculator with Selenium Appium



## Technology used:

- Appium Inspector
- Gradle
- Java
- Selenium Webdriver
- Appium
- Intellij 
- Android Studio


## How to run this project:

- Clone this project
- Open Android Studio and Open the APK file:
- Set required configuration 
- Hit this command in cmd for checking the connectivity with emulator : ``adb devices``
- Open Appium Server with following command: ```appium -p 4723```
- Open Appium Inspector
- Open Intellij Idea
- Hit the following command into the terminal: ```gradle clean test```

## How to generate Allure Report 
-  use these commands: ```allure generate allure-results --clean -o allure-report``` & ```allure serve allure-results```


## Project scenerio:

**If an user take loan (?) tk from a bank with interest of (?)% and  want to give (?) tk per month as EMI (installment) and processing fee (?)%, how many time period it will take to complete the loan? Take the values from dataset and assert the monthly EMI, total interest, processing fee amount and total payment from the result view. 

created  dataset using following values:

Amount | Interest | EMI | Processing Fee | Monthly EMI | Total Interest | Processing Fee | Total Payment | Period (Year) | Period (Month)**

**For solve this question, create a dataset using following values:**

```
Amount | Interest | EMI | Processing Fee | Monthly EMI | Total Interest | Processing Fee | Total Payment | Period (Year) | Period (Month)

100000 | 6 | 2000 | 2% | 2000 | 15361.08 | 2000 | 115361.08 | 4 | 10
200000 | 8 | 5000 | 2% | 5000 | 33391.61 | 4000 | 233391.61 | 3 | 11

250000 | 7 | 8000 | 1.5% | 8000 | 26804.51 | 3750 | 276804.51 | 2 | 11

50000 | 10 | 1000 | 5% | 1000 | 14949.12 | 2500 | 64949.12 | 5 | 5

```
## Prerequisites:

- Install Android Studio latest version
- Install Appium Inspector
- Install jdk 8 or any LTS version
- Configure ANDROID_HOME, JAVA_HOME and GRADLE_HOME

## Allure Report:

![y22](https://user-images.githubusercontent.com/123531000/224468028-c5831fc8-8ff3-44c1-ad2c-66fa13d0be1a.png)
![y11](https://user-images.githubusercontent.com/123531000/224468030-d9df1b8a-9813-4392-91f0-43f048932d4d.png)


# Video Outp


[screen-capture (4).webm](https://user-images.githubusercontent.com/123531000/224468044-3caf25d4-740a-4d68-8568-3107d00a1f9c.webm)
