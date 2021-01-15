Инструмент для мутации данных, получает на вход файл, мутирует его содержимое и записывает результат.
Для запуска необходимо запустить radamsa.exe с cygwin1.dll в одной папке через консоль.

Пример:
radamsa -n 100 fuzz1.txt >> fuzz2.txt
,где n- количество мутированных значений на выходе, fuzz1.txt - мутируемое значение, fuzz2.txt - результат.

https://gitlab.com/akihe/radamsa/
https://github.com/vah13/radamsa/releases/tag/v0.5
