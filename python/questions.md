### Чем отличается сравнение is от ==?
`==` проверяет, одинаковые ли значения у переменных. `is` проверяет, указывают ли переменные на один и тот же объект.
> a = [1, 2, 3]
>
> b = a
>
> b is a `True`
>
> b == a `True`
>
> id(a) `4369080704`
> id(b) `4369080704`
> 
> b = a[:]
> 
> b is a `False`
>
> b == a `True`
>
> id(a) `4369080704`
> id(b) `4369080896`

### Может ли список быть ключом словаря?
Нельзя использовать списки в качестве ключей словаря, так как списки могут быть изменены на месте с помощью индексов, срезов или методов, таких как append() и extend() . Лучше всего рассматривать словарь как набор пар "ключ-значение" с требованием, чтобы ключи были уникальными в пределах одного словаря.

### Что такое self?
self - ссылка на экземпляр класса

### Как передать неопределенное количество параметров в функцию?
C помощью специальных синтаксических конструкций: *args и **kwargs . 
*args используется для передачи неопределенного числа неименованных аргументов в виде кортежа.
**kwargs работает так же, как и *args, но вместо кортежа используется словарь. 

### Какая сложность алгоритма получения занчения из словаря?
O(1). Более подробную информацию можно получить по [ссылке](https://proglib.io/p/slozhnost-algoritmov-i-operaciy-na-primere-python-2020-11-03)
