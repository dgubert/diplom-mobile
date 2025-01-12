
<h1 align="center">Дипломная работа (MOBILE).<br>Приложение Википедия.</h1>


##  **Содержание:**

---

* [Технологии и инструменты](#технологии-и-инструменты)
* [Проверки](#-проверки)
* [Запуск тестов в Jenkins](#-запуск-тестов-в-jenkins)
* [Allure и TestOps Reports](#--allure-report)

## Технологии и инструменты:

---


| Java                                                                                         | IntelliJ  <br>  Idea                                                                                                 | GitHub                                                                                                           | JUnit 5                                                                                                           | Gradle                                                                                                     | Selenide                                                                                                         | Appium                                                                                                                | Allure <br> Report                                                                                                         | Jenkins                                                                                                          | TestOps                                                                                                  |
|:---------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| <a href="https://www.java.com/"> <img src="media/logo/Java.svg" height="50" width="50"/></a> | <a href="https://www.jetbrains.com/idea/"><img height="50" src="media/logo/Intelij_IDEA.svg" width="50"/></a> | <a href="https://github.com/"><img alt="Github" height="50" src="media/logo/GitHub.svg" width="50"/></a> | <a href="https://junit.org/junit5/"><img alt="JUnit 5" height="50" src="media/logo/JUnit5.svg" width="50"/></a> | <a href="https://gradle.org/"><img alt="Gradle" height="50" src="media/logo/Gradle.svg" width="50"/></a> | <a href="https://selenide.org/"><img alt="Selenide" height="50" src="media/logo/Selenide.svg" width="50"/></a> | <a href="http://appium.io/docs/en/latest/"><img alt="Appium" height="50" src="media/logo/appium.png" width="50"/></a> | <a href="https://github.com/allure-framework"><img alt="Allure" height="50" src="media/logo/Allure_Report.svg" width="50"/></a> | <a href="https://www.jenkins.io/"><img alt="Jenkins" height="50" src="media/logo/Jenkins.svg" width="50"/></a> | <a href="https://qameta.io"><img alt="TestOps" height="50" src="media/logo/testops.svg" width="50"/></a> |


## <img height="25" src="media/pic/logo.png" width="25"/> Проверки:

---

- ✓ *Проверка работы поиска статей*
- ✓ *Проверка открытия одной из статей*


## <img height="25" src="media/logo/Jenkins.svg" width="25"/> Запуск тестов в Jenkins:

---

**Сборка в [Jenkins](https://jenkins.autotests.cloud/job/diplom-mobile/)**
- *BRANCH_NAME - ветка разработки тестов, по умолчанию master*
- *PLATFORM - платформа тестов, по умолчанию android*

**Команда для запуска тестов**
```bash  
clean test -Denv=android
clean test -Denv=ios
```

## <img height="25" src="media/logo/Allure_Report.svg" width="25"/></a>  <a name="Allure"></a>Allure и TestOps Reports	</a>

---

## Основная страница Allure отчёта

<p align="center">  
<img title="Allure Overview Dashboard" src="media/pic/allure_main.png" width="850">  
</p>  

## Тест-кейсы Allure

<p align="center">  
<img title="Allure Tests" src="media/pic/allure_suites.png" width="850">
</p>

## Основная страница TestOps отчёта

<p align="center">  
<img title="Allure Overview Dashboard" src="media/pic/allure_main.png" width="850">  
</p>  

## Тест-кейсы TestOps

<p align="center">  
<img title="Allure Tests" src="media/pic/testops.png" width="850">
</p>