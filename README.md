# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

08.05.21 - 08.05.21 было проведено Functional testing приложения Credit Card Number Validator.

На тестирование затрачено: 1h:00m

В результате тестирования выявлены следующие дефекты:
* [Номера карты AmExp и UATP из 15 цифр, InterPayment/Maestro/Visa/ChinaUnionPay(18,19 цифр), DinersClub(14 цифр) не проходят валидацию в приложении](https://github.com/Alexsandra2203/jdemoHW1/issues/1#issue-881204488)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:

* [Номера банковских карт](https://www.banki.ru/wikibank/nomer_bankovskoy_kartyi/)

* [Алгоритм Луна](https://ru.wikipedia.org/wiki/%D0%90%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC_%D0%9B%D1%83%D0%BD%D0%B0)

* [test case](https://docs.google.com/spreadsheets/d/1NK5VIIWW-rsWnrSv1d302nYBnlWc_Vtzk17q96N9q0I/edit#gid=0)



В качестве тестовых данных использовались данные:
* [Генератор номеров кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* Название ОС:       Майкрософт Windows 10 Домашняя
* Версия ОС:         10.0.19042 Н/Д построение 19042; тип системы - x64
* версия Java 11
* ПО:
* Браузер Chrome 90.0.4430.93 OE
* IntelliJ IDEA Community Edition 2021.1.1
