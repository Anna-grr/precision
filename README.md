# Отчёт о тестировании приложения "Precision"
## Краткое описание
11.12.2020 было выполнено тестирование кода, предназначенного начислять дополнительный бонус новым клиентам компании. 

## Описание тестов
Было проведено функциональное тестирование кода с целью проверки его работоспособности.

## Результаты

В результате тестирования выявлены следующие дефекты:

* [При операции сложения двух десятичных дробей типа double выводится длинная дробь](https://github.com/Anna-grr/precision/issues/1#issue-762493838)

## Общие рекомендации
Передать обнаруженный дефект на рассмотрение разработчикам. Результат вычислений не позволит корректно начислять бонусы, необходимо предусмотреть округление.