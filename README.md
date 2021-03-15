# Отчёт о тестировании программы подсчета суммы на счете

## Краткое описание

15.03.21 - 15.03.21 было проведено smoke-тестирование приложения для подсчета суммы на счёте.

На тестирование затрачено: 0.5 часа

В результате тестирования выявлены следующие дефекты:
* [Программа подсчета суммы на счету вернула неверный результат сложения](https://github.com/dunaev-k-s/java-hw-2-1/issues/1)

## Описание процесса тестирования




В качестве тестовых данных использовались данные из [Технического задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):

* сумма на счету `2_000_000_000`
* сумма перевода `500_000_000`

Тестирование производилось в следующем окружении:
* Windows 10 x64
* openJDK 11.0.2
* IntelliJ IDEA 2020.3.2

![Screenshot](Images/1.png)