# Отчет о тестировании Precision
## Краткое описание
21.08.2020 было проведено было проведено функциональное тестирование приложения Precision.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
- [Некорректный результат при сложении](https://github.com/Rusdos/Netology-java2.2/issues/1#issue-683342466)

## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:

- #### Подсчет спец.бонуса позитивные  

#### Предусловия 
Установить IntelliJ IDEA согласно 
[Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

#### Шаги
1. запустить IntelliJ IDEA
1. в IntelliJ IDEA открыть папку с проектом
1. в папке src открыть класс Main
1. нажать Ctrl+Shift+F10

В качестве тестовых данных использовались данные :

- регулярный бонус =  0.3 ; специальный бонус = 0.6;

Тестирование производилось в следующем окружении:

- ОС Windows 10 x64
- IntelliJ IDEA 2020.2 (Community edition) Runtume version 11.0.7+10-b944.20 amd64
