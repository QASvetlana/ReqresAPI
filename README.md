
## Проект для https://reqres.in/

![image](src/files/reqres.jpg)

## Использованы технологии:
|  Java  | Gradle | Junit5 | Selenide | GitHub | Jenkins | Allure Report |   Jira   | Rest-Assured|
|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|:-------:|
| <img src="images/logo/Java.png" width="40" height="40"> | <img src="images/logo/Gradle.png" width="40" height="40"> | <img src="images/logo/JUnit5.png" width="40" height="40"> | <img src="images/logo/Selenide.png" width="40" height="40"> | <img src="images/logo/Github.png" width="40" height="40"> | <img src="images/logo/Jenkins.png" width="40" height="40"> | <img src="images/logo/Allure_Report.png" width="40" height="40"> | <img src="images/logo/Jira.png" width="40" height="40"> | <img src="images/logo/Rest-Assured.png" width="40" height="40"> |

___

## Запуск тестов происходит в CI [Jenkins](https://jenkins.autotests.cloud/job/ReqresAPI/)

![image](src/files/jenkins.jpg)

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

![image](src/files/allure.jpg)

___
___

## Тестовая документация хранится в Allure TestOpts

![image](src/files/allureTestopts.jpg)
![image](src/files/allureTestopts2.jpg)

___

## Уведомления о прохождение тестов отправляются в Telegram

![image](src/files/telegram.jpg)
___