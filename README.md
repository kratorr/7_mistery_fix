# Решатель квадратных уравнений

Программа вычисляет корни квадратного уравнения общего вида: ![y=ax^2+bx+c=0](https://wikimedia.org/api/rest_v1/media/math/render/svg/24c2ce44ca552049d96088988f5d83f6763c059a)

# Как использовать

Функция get_roots, принимает 3 обязательных аргумента

Общий вид:
```python
import quadratic_equation

print(quadratic_equation.get_roots(a, b, c))
```
Пример:
```python
import quadratic_equation

print(quadratic_equation.get_roots(1, 2, -3))
```
(-3.0, 1.0)

# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
