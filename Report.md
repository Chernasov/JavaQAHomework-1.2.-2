# Отчёт о тестировании Precision

## Краткое описание

10.08.2021 было проведено тестирование методом белого ящика приложения Precision.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
<!--* [Неправильный результат вычислений суммы](https://github.com/Chernasov/JavaQAHomework-1.2.-1/issues/1#issue-964920989)
-->
## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
-

В качестве тестовых данных использовался код:
```java
public class Main {
public static void main(String[] args) {
double regularBonus = 0.3;
double specialBonus = 0.6;
double totalBonus = regularBonus + specialBonus;
System.out.println(totalBonus);
}
}
```
Ожидался результат totalBonus = 0.9

Тестирование производилось в следующем окружении:
* 20H2 x64 Windows 10 Домашняя для одного языка
* Java version "11.0.11" 2021-04-20