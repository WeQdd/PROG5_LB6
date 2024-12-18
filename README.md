# Лабораторная работа 6. Использование шаблона «Декоратор»
## Студент 3 курса Антипов Арсений

Цель работы
Примените паттерн декоратор и реализуйте объектно-ориентированную версию программы получения курсов валют с сайта Центробанка таким образом, чтобы:
* было возможно использовать базовую версию для получения информации о валютах (возвращает словарь со структурой, описанной в одной из предыдущих лабораторных работ) (class CurrenciesList);
* было возможно применить декоратор к базовой версии и получить данные в формате JSON (class ConcreteDecoratorJSON);
* было возможно использовать декоратор к базовой версии (CurrenciesList) или к другому декоратору (ConcreteDecoratorJSON) и получить данные в формате csv (class ConcreteDecoratorCSV).

Вывод результата работы программы:

![image](https://github.com/user-attachments/assets/221285aa-1579-4bb6-ae66-501e2cc71b7a)

class ConcreteDecoratorJSON:

![image](https://github.com/user-attachments/assets/ffd73652-ae3e-4603-b8c3-49a1be8c17ab)

class ConcreteDecoratorCSV:

![image](https://github.com/user-attachments/assets/6bdd7905-c633-4493-9571-164317f43f3d)
