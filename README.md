# Лабораторна робота 4

## Cинтаксичний аналізатор

## Граматика задана у файлі input.txt

S->AB
A->a
A->e
B->b
B->e

## Приклади:

1)

Вхідний рядок: ac

Вихідні дані:

Grammar parsed from grammar file:
0.  S -> ab
1.  S -> ac

The non terminals in the grammar are: S
The terminals in the grammar are: $ ab ac

Firsts list:
S : ab ac

Follows list:
S : $

Parsing Table:
   $ ab ac
S  0 0 1

RES = ca
Input string is accepted

2)

Вхідні дані: aa

Grammar parsed from grammar file:
0.  S -> ab
1.  S -> ac

The non terminals in the grammar are: S
The terminals in the grammar are: $ ab ac

Firsts list:
S : ab ac

Follows list:
S : $

Parsing Table:
   $ ab ac
S  0 0 1

Input string is invalid