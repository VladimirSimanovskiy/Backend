Класс TextHandler принимает на вход строку.
Для класса TextHandler доступны следующие методы:
1) capitalize() - возвращает строку в которой преобразует первую букву к верхнему регистру, а все остальные буквы к нижнему;
2) punctuation() - возвращает строку, в которой соблюдаются следующие правила расстановки пробелов:
                   a) после знаков препинания должны стоять пробелы
                   b) перед знаками препинания пробелов быть не должно
                   c) лишние, стоящие рядом, пробелы удаляются
3) wordCounter() - возвращает число: количество слов в строке. С целью соблюдения единой логики для методов класса TextHandler,
                   первоначально строка форматируется согласно правилам, указанным для метода punctuation();
4) wordsFrequency() - возвращает объект, ключами которого являются уникальные (без учета регистра) слова в переданной строке,
                      а значениями - число, показывающее сколько раз данное слово встретилось в тексте.