# Второе занятие


## Условные операторы.

### операторы сравнения
```bash
"==", "!=", ">", ">=", "<", "<=", "===", "!=="
```
<br />

```php
<?php
echo 2 == 3 . "\n";
echo 2 != 3 . "\n";
echo 2 > 3 . "\n";
echo 3 == "3" . "\n";
echo 3 === "3" . "\n";
```
<br />

```php
$a = 3 > 2;
var_dump($a);

$val1 = 10;
$val2 = 20

var_dump($val1 <= $val2);
```
<br />
<br />

### Блок if
```php
if (условие) {
    // код, который выполняется если условие истинно
}
```

<br />

### Пример if
```php
$temperature = 15;
if ($temperature < 20) {
    echo "Надень куртку!";
}
```

### Пример if
```php
$temperature = 15;
if ($temperature < 20) {
    echo "Надень куртку!";
}

if ($temperature >= 20) {
    echo "Куртка не понадобиться!";
}
```


### Блок if...else
```php
if (условие) {
    // код если условие истинно
} elseif (другое условие) {
    // код если другое условие истинно
}
```

### Пример if...else
```php
$temperature = 15;

if ($temperature < 20) {
    echo "Надень куртку!";
} else {
    echo "Куртка не понадобиться!";
}
```

### Блок if...else...elseif
```php
if (условие) {
    // код если условие истинно
} elseif (другое условие) {
    // код если другое условие истинно
} else {
    // код если ни одно условие не выполнено
}
```

### Пример if...else...elseif
```php
$temperature = 15;

if ($temperature < 10) {
    echo "Очень холодно!";
} elseif ($temperature < 20) {
    echo "Прохладно!";
} else {
    echo "Тепло!";
}
```

### Блок switch
```php
switch (выражение) {
    case значение1:
        // код если выражение равно значению1
        break;
    case значение2:
        // код если выражение равно значению2
        break;
    default:
        // код если ни одно значение не совпало
}
```

### Пример switch
```php
$day = "понедельник";

switch ($day) {
    case "понедельник":
        echo "Начало рабочей недели!";
        break;
    case "суббота":
        echo "Выходные!";
        break;
    case "воскресенье":
        echo "Выходные!";
        break;
    default:
        echo "Рабочий день!";
}
```

<br />

### Задачи на уроке.
1. [Больше-меньше](https://acmp.ru/asp/do/index.asp?main=topic&id_course=2&id_section=10&id_topic=2)
2. [Зарплата](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=7)
3. [Арифметика](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=8)

---


### Домашнее задание.
1. [Счастливый билет](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=9)
2. [Две окружности](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=2&id_problem=10)
