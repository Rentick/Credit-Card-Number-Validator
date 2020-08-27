# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

27.08.2020 - 27.08.2020 было проведено валидное значение номерации карт программы Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* https://github.com/Rentick/Credit-Card-Number-Validator/issues/1

## Описание процесса тестирования

В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* VISA Carte:
  4916435318401757004 Ожидаемый результат - ОК
* Diners Club - Carte Blanche:
  30373761033930 Ожидаемый результат - ОК

Тестирование производилось в следующем окружении:
* Windows 10, 64 bit
* Java 11.0.08
