### Hexlet tests and linter status:
[![Actions Status](https://github.com/alexMAG576/java-project-78/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/alexMAG576/java-project-78/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/dd09bc2b815499914eff/maintainability)](https://codeclimate.com/github/alexMAG576/java-project-78/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/dd09bc2b815499914eff/test_coverage)](https://codeclimate.com/github/alexMAG576/java-project-78/test_coverage)

Валидатор данных

Эта библиотека разработана для проверки различных объектов на соответствие установленным ограничениям с помощью метода isValid(), имеющего аргумент типа integer, String или Map.

Валидатор создает схемы, используя перечисленные ниже методы, которые содержат ограничения для каждого из перечисленных выше типов объектов

1) string() - создайте схему для проверки строки и добавте ограничения приведенными ниже методами:
    required() - ограничивает нулевые и пустые строки;
    minLength() - ограничивает строки длиной меньше, чем задано аргументом;
    contains() - требует, чтобы строка содержала строку, указанную в аргументе.

2) number() - создайте схему для проверки int и добавте ограничения приведенными ниже методами:
    required() - ограничьте значение null;
    positive() - ограничьте числа, меньшие или равные нулю;
    range() - требуется, чтобы число находилось в диапазоне, определенном двумя аргументами.

3) map() - создайте схему для проверки Map и добавьте ограничения приведенными ниже методами:
    required() - ограничьте нулевую карту;
    sizeof() - ограничьте карту размером, установленным аргументом;
    shape() - за исключением карты, содержащей ограничения в качестве значений элементов. 

### asciinema
[![asciicast](https://asciinema.org/a/CoKpuyxZawoS2nxA1rtzy5OT4.svg)](https://asciinema.org/a/CoKpuyxZawoS2nxA1rtzy5OT4)
