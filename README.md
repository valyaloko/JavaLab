# Практикум по программированию на Java

## список работ

* Work 1. Adress Book 


## Структура папок

<pre>
solution
-SpecialtySurnameInitials
--work1
--work2
  ...
--workN
</pre>
  
Specialty - направление подготовки (bit, biz, inb, ist, ivt, pin, pmi, poi)
SurnameName - Фамилия (транслит)
Initials - Инициалы (транслит)

Например, poiIvanovII, bitPetrovMI


## Правила именования

**Все названия набираются лининицей**

### Пакеты (package name.surname.specialty.packagename)

* name - имя
* surname - фамилия
* specialty - направление подготовки
* packagename- имя пакета (обычно в стиле lowerCamelCase)

### Классы (class SClassnameN)

S - Первая (заглавная) буква фамилии
N - Первая (заглавная) буква имени
Classname - имя класса (обычно совпадает с именем пакета в стиле UpperCamelCase)

### Методы (void sMethodnameN())

s - Первая (строчная) буква фамилии
N - Первая (заглавная) буква имени
Methodname - имя метода

### Переменные, поля классов (svariablenanen)

s - Первая (строчная) буква фамилии
n - Первая (строчная) буква имени
variablenane - имя метода (обычно в стиле lowerCamelCase, UpperCamelCase, snake_case) 

*Исключение* могут составлять однобуквенные имена переменных, используемых в качестве итераторов локальных циклов, например i,j,k.


