# Отчёт о тестировании Credit Card Number Validator
## Краткое описание
26.11.2021 - 26.11.2021 было проведено ручное функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:

* [Не прошел валидацию корректный девятнадцатизначный номер VISA](https://github.com/Averagegithubusername/javahw1.2/issues/1#issue-1064021349)  
* [Не прошел валидацию корректный номер American Express (AMEX)](https://github.com/Averagegithubusername/javahw1.2/issues/2#issue-1064027465)  

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

* [Задача №2 - Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md#%D0%B7%D0%B0%D0%B4%D0%B0%D1%87%D0%B0-2---credit-card-number-validator)  

В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html#fakeNumbers):

* [main.java](https://github.com/Averagegithubusername/javahw1.2/blob/6913f7d30259327da57b85786eab59b3e795d712/src/Main.java)  
* 4532512134043283478 - девятнадцатизначный номер VISA  
* 371329984317770 - номер American Express (AMEX)


Тестирование производилось в следующем окружении:

* Windows 10 Домашняя, версия 20H2, 64-разрядная  
* Java version 11.0.13  
* IntelliJ IDEA 2021.2.3 (Community Edition)