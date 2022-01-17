
## Проект для https://reqres.in/

![image](src/test/resources/files/reqres.jpg)

## Использованы технологии:
|  Java  | Gradle | Junit5 | Selenide | GitHub | Jenkins | Allure Report |   Jira   | Rest-Assured|
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| ![Image alt](https://github.com/QASvetlana/Reqres/blob/master/images/logo/Java.png) | <img src="images/logo/Gradle.png" width="40" height="40"> | <img src="images/logo/JUnit5.png" width="40" height="40"> | <img src="images/logo/Selenide.png" width="40" height="40"> | <img src="images/logo/Github.png" width="40" height="40"> | <img src="images/logo/Jenkins.png" width="40" height="40"> | <img src="images/logo/Allure_Report.png" width="40" height="40"> | <img src="images/logo/Jira.png" width="40" height="40"> | <img src="images/logo/Rest-Assured.png" width="40" height="40"> |

___

## Запуск тестов происходит в CI [Jenkins](https://jenkins.autotests.cloud/job/ReqresAPI/)

![image](src/test/resources/files/jenkins.jpg)

Запуск тестов:
```bash
gradle clean test
```

Генерация отчета:
```bash
allure serve
```
```bash
build/allure-results
```
___

## Генерация отчета происходит в Allure Report

![image](src/test/resources/files/allure.jpg)

___
___

## Тестовая документация хранится в Allure TestOpts

![image](src/test/resources/files/allureTestopts.jpg)
![image](src/test/resources/files/allureTestopts2.jpg)

___

## Уведомления о прохождение тестов отправляются в Telegram

![image](src/test/resources/files/telegram.jpg)
___