# Homework-32
English:Example of using GMoke and GTest

Each test is located in its own header file.

DBConnection - virtual class, interface
Mockclass - creates mock objects to isolate tests
ClassThatUsesDB - instead of an interface, uses objects from Mockclass for GTest

Русский:Пример использования GMoke и GTest

Каждый тест расположен в своем заголовочном файле.

DBConnection - виртуальный класс, интерфейс
Mockclass - создает мок-объекты для изолирования тестов
ClassThatUsesDB - вместо интерфейса использует для GTest объекты из Mockclass 
