# Игра Виселица
![alt-текст][logo]

Игрок отгадывает загаданное слово путем ввода букв с клавиатуры, он может ошибиться 7 раз. После каждой ошибки в консоли вырисовывается туловище.
Если туловище в виселице нарисовано полностью, то отгадывающий игрок проигрывает, считается повешенным. Если игроку удаётся угадать слово, он выигрывает.

## Запуск игры
Для запуска вам потребуется установить последнюю версию Ruby на ваш компьютер. Далее в терминале ввести команду в каталоге с программой:
~~~
ruby main.rb
~~~
Пример запуска:
~~~
Слово: __ __ __ __ __ __
            _______
            |/
            |
            |
            |
            |
            |
            |
            |
          __|________
          |         |

Ошибки (0): 
У вас осталось ошибок: 7

Введите следующую букву: 
~~~
Чтобы добавить новые слова, нужно открыть файл _words.txt_ в папке _data/_ и внести нужные изменения.

Автор: Крохмалюк Сергей ([grimr5](https://github.com/Grimr5))

[logo]: https://minigames.mail.ru/info/pictures/image/hangman_360_234.jpg "Текст заголовка логотипа 1"
