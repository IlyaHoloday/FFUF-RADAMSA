Инструмент для редактирования и отправки пакетов на тестируемое веб-приложение.

Пример:
ffuf -request ./req.txt -w ./result1.txt:FUZZ1,./result2.txt:FUZZ2 -x http://127.0.0.1:8080 -p 15 -rate 1 -timeout 60 -u http://10.2.0.33:8080/bWAPP/xss_post.php -b "PHPSESSID=d26e23c007edc07b118b15a1f4c42a82; security_level=0"

https://github.com/ffuf/ffuf
