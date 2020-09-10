# Отчёт о тестировании приложения Credit Card Number Validator

## Краткое описание

09.09.2020-10.10.2020 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 5 часов

В результате тестирования выявлены следующие дефекты:
* [Validation error of valid 15-digit credit card](https://github.com/AigulD/Credit-card-number-validator/issues/1)
* [Validation error of valid 19-digit credit card](https://github.com/AigulD/Credit-card-number-validator/issues/2)
* [Validation error of valid 15-digit credit card](https://github.com/AigulD/Credit-card-number-validator/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)
* Баг-репорт

В качестве тестовых данных использовались номера кредитных карт сгенерированные на сайте [wtool.io](https://wtools.io/ru/credit-card-generator):
* Dankort 5019225651103757 (Result is OK)
* DCI 3000458280853635	(Result is OK)
* JCB 3573051219738709 (Result is OK)	
* InstaPayment 6375604924583738 (Result is OK) 
* InterPayment 6364521642195640 (Result is OK)
* Maestro 6390767891533274 (result is OK)
* Mastercard 2255829040476731 (Result is OK)
* RuPay 6522034508466088 (Result is OK)
* Verve 6500186540646501 (Result is OK)
* Visa 4140977617239043 (Result is OK)

Тестирование производилось в следующем окружении:
* Устройство: Lenovo G580
* ОС: Windows 10 Pro-64 bit
* Java version: "11.0.8" 2020-07-14