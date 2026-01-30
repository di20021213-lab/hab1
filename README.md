Запустите два simple python сервера на своей виртуальной машине на разных портах
Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
Настройте балансировку Round-robin на 4 уровне.
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.
[backup (1).txt](https://github.com/user-attachments/files/24967400/backup.1.txt)

<img width="1275" height="737" alt="netology02" src="https://github.com/user-attachments/assets/9b3f4c16-6091-4162-8633-37e2d07e2be8" />
<img width="947" height="826" alt="netology01" src="https://github.com/user-attachments/assets/05354d4c-f914-4e45-aab5-0ea4569823fe" />


Задание 2
Запустите три simple python сервера на своей виртуальной машине на разных портах
Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
[1.txt](https://github.com/user-attachments/files/24967423/1.txt)
<img width="1348" height="545" alt="netology04" src="https://github.com/user-attachments/assets/465a4fa7-dc53-4f55-94d3-c2b233a6e469" />

