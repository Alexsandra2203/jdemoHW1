# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

08.05.21 - 08.05.21 было проведено Functional testing приложения Credit Card Number Validator.

На тестирование затрачено: 1h:00m

В результате тестирования выявлены следующие дефекты:
* Номера карт Мир и InterPayment(16 цифр), InterPayment/Maestro/Visa/ChinaUnionPay(18,19 цифр), AmericanExp и UATP(15 цифр), DinersClub(14 цифр)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Bug report https://github.com/Alexsandra2203/jdemoHW1/issues/1#issue-881204488

В качестве тестовых данных использовались данные:
Генератор номеров кредитных карт
https://www.freeformatter.com/credit-card-number-generator-validator.html

Тестирование производилось в следующем окружении:
* Название ОС:       Майкрософт Windows 10 Домашняя
* Версия ОС:         10.0.19042 Н/Д построение 19042; тип системы - x64
* версия Java 11
* ПО:
* Браузер Chrome 90.0.4430.93 OE
* IntelliJ IDEA Community Edition 2021.1.1
