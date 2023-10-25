### <font color="Bluie"> Общее описание решений

1. <font color="Cyan"> Скопировал репозиторий с помощью команды git clone>
2. Открыл папку geometric_lib с помощью команды cd
3. Создали ветку new_368340 и перешли на неё с помощmю команды git branch -b
4. Создал файл rectangle.py  помощью команды echo >
5. Вставил код в файл
6. Сохранили добавление файла с помощью команды git add
7. Добавил коммит  с помощью команды git commit -m
8. Создал файл triangle.py с помощью команды echo >
9. Вставил код в файл
10. Сохранили добавление файла с помощью команды git add
11. Исправили ошибку в файле rectangle.py
12. Сохранили изменения в файле с помощью команды git add
13. Добавил коммит  с помощью команды git commit -m
14. Построили граф истории всего репозитория с однострочным выводом коммитов с помощью команды git log --oneline --graph --all
15. Построили граф истории текущей ветки с однострочным выводом коммитов с помощью команды git log --oneline --graph
16. Взяли хэши двух последних коммитов из истории и посмотрели внесенные изменения с помощью команды git show
17. Перешли в main  с помощью команды git checkout
18. Сделали merge в ветку main с помощью команды git merge
19. Изменили origin с помощью команды git remote set-url origin
20. Отправили репозитерий на локальный репозиторий(GitHub) с помощью команды git push -u origin
21. Удалили ветку <new_368340> с помощью команды git branch -d
### Описание каждой функции с примерами вызова
#### rectangle
    def area(a, b):
    return a * b
Принимает числа a и b, возвращает площадь прямоугольника со сторонами a и b

example:

input: 3 3

output:9

    def perimeter(a, b):
    return (a + b)*2
Принимает числа a и b (стороны прямоугольник), возвращает периметр прямоугольника со сторонами a и b'''

example:

input: 5 5

output: 20

#### square
    def area(a):
    return a * a
Принимает число a (сторона квадрата), возвращает площадь квадрата со стороной a

example:

input: 5

output: 25

    def perimeter(a):
    return 4 * a

Принимает число a (сторона квадрата), возвращает периметр квадрата со стороной a

example:

input: 4

output: 16

#### triangle
    def area(a, h):
    return a * h / 2

Принимает числа a и h (основавние и высота треугольника), возвращает площадь треугольника с основанием a и высотой h

example:

input: 2 5

output: 5

    def perimeter(a, b, c):
    return a + b + c

Принимает числа a, b, c (стороны треугольника), возвращает периметр треугольника со сторонами a, b, c

example:

input: 2 2 3

output: 7

#### circle

    import math

    def area(r):
    return math.pi * r * r
Подключили библиотеку math

Принимает число r(радиус),Возвращает площадь круга с радиусом r

example:

input: 5

output: 78.540

    def perimeter(r):
    return 2 * math.pi * r

Принимает число r(радиус), Возвращает периметр круга с радиусом r

example:

input: 5

output: 31.416

## Коммиты

### commit 89cb7e682d9634e05fba72227948eda79bfcdae3 (HEAD -> main, origin/main, origin/HEAD)
    Author: geg567 <sergey.kononov.04@gmail.com>
    Date:   Wed Oct 25 14:03:02 2023 +0300

    fixed perimeter in rectangle.py

### commit 2f934a25898756179a6682a0ad6f8f13d33c5665
    Author: geg567 <sergey.kononov.04@gmail.com>
    Date:   Wed Oct 25 13:58:49 2023 +0300

    added new file
