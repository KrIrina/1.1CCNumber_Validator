# Отчёт о тестировании Credit Card Validator

## Краткое описание

08.08.2021 - 08.08.2021 было проведено тестирование функциональности "Валидация номера банковской карты" приложения "Приём платежей с банковских карт".

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* https://github.com/KrIrina/1.1CCNumber_Validator/issues/1#issue-963871113
* https://github.com/KrIrina/1.1CCNumber_Validator/issues/2#issue-963877143

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Набор тест-кейсов https://docs.google.com/spreadsheets/d/1ZxEeFfZ3mTcnsVaXTf3MvnqLkroeBP9tgQNYE29HdJ8/edit?usp=sharing
* Код программы https://docs.google.com/document/d/1__2eiDCUCLfDHZtwijHsewmAG2Dqop2AR5jVZnuOkio/edit?usp=sharing


В качестве тестовых данных использовались данные https://www.freeformatter.com/credit-card-number-generator-validator.html:
* 4748882857061162  Result is ОК
* 4716299142571806  Result is ОК
* 4556379373992924861  Result is ОК
* 6011303799156346  Result is ОК
* 6011432563957413  Result is ОК
* 30318801996661  Result is ОК

Тестирование производилось в следующем окружении:
* OC Window 7 x64
* Java 11.0.12.
