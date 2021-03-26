# regexp

Заготовка репозитория для работы по регулярным выражениям

## Упражнение №1

Сделайте форк [репозитория] ([локальный МФТИ]), в котором содержатся
заготовки программ для работы.

В файл [simple_match.py] впишите требуемые регулярные выражения
`REGEXP_1`, `REGEXP_2` и т.д., после чего
запустите на выполнение тесты из файла [simple_match_test.py]. Добейтесь
прохождения всех тестов.

Обратите внимание, что в файле указано ожидаемое поведение программы для
конкретного набора строк, а не чёткая формулировка задания наподобие
«напишите регулярное выражение, соответствующее строке, состоящей только
из прописных букв». Это сделано сознательно: дело в том, что при помощи
регулярных выражений обычно решают некую вполне конкретную задачу, а не
какую-то абстрактную общую задачу. И поэтому во многих задачах из этой
работы возможно более одного правильного решения. Например, строка
`ABabAB` соответствует как регулярному выражению
`\[ABab\]+`, так и выражению `\^A.\*B\$`, да и
ещё достаточно большому количеству других выражений.

  [репозитория]: https://github.com/mipt-cs-on-python3/regexp
  [локальный МФТИ]: http://10.55.169.235/regexp
  [simple_match.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_match.py
  [simple_match_test.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_match_test.py

## Упражнение №2

В файл [simple_search.py] впишите требуемые регулярные выражения
`REGEXP_1`, `REGEXP_2` и т.д., после чего
запустите на выполнение тесты из файла [simple_search_test.py].
Добейтесь прохождения всех тестов.

  [simple_search.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_search.py
  [simple_search_test.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_search_test.py

## Упражнение №3

В файл [simple_findall.py] впишите требуемые регулярные выражения
`REGEXP_1`, `REGEXP_2` и т.д., после чего
запустите на выполнение тесты из файла [simple_findall_test.py].
Добейтесь прохождения всех тестов.

  [simple_findall.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_findall.py
  [simple_findall_test.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_findall_test.py

## Упражнение №4

В файл [simple_sub.py] впишите требуемые регулярные выражения и строки
замены `REGEXP_1` / `REGEXP_1\_REPL`,
`REGEXP_2` / `REGEXP_2\_REPL` и т.д., после чего
запустите на выполнение тесты из файла [simple_sub_test.py]. Добейтесь
прохождения всех тестов.

  [simple_sub.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_sub.py
  [simple_sub_test.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/simple_sub_test.py

## Упражнение №5

В файл [advanced_sub.py] впишите требуемые регулярные выражения и строки
замены `REGEXP_1` / `REGEXP_1\_REPL`,
`REGEXP_2` / `REGEXP_2\_REPL` и т.д., после чего
запустите на выполнение тесты из файла [advanced_sub_test.py]. Добейтесь
прохождения всех тестов.

  [advanced_sub.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/advanced_sub.py
  [advanced_sub_test.py]: https://github.com/mipt-cs-on-python3/regexp/blob/master/advanced_sub_test.py
