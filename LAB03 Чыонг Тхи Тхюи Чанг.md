1. cd /c/Users/Admin/student/truongthithuytrang/backup
2.echo "Привет, мир! Меня зовут ЧЬОНГ ТХИ ТХЮИ ЧАНГ." > message.txt
3.echo "Сегодня мы изучаем Linux." >> message.txt
4.grep "Linux" message.txt
6.ip addr | grep "inet " | grep -v "127.0.0.1"
7.ip addr | grep "inet " | grep -v "127.0.0.1" | grep -Eo '([0-9]{1,3}\.){3}[0-9]{1,3}'
8.echo "" >> message.txt
echo "Это сообщение отправлено с $(hostname) по адресу $(ip addr | grep "inet " | grep -v "127.0.0.1" | grep -Eo '([0-9]{1,3}\.){3}[0-9]{1,3}')" >> message.txt
9.ping <IP-адрес_партнера>
10.scp message.txt <имя_пользователя_партнера>@<IP-адрес_партнера>:/tmp/
11.ssh <имя_пользователя_партнера>@<IP-адрес_партнера>
cat /tmp/message.txt
exit
12.cat message.txt
13.nano greet.sh
#!/bin/bash
echo "Как вас зовут?"
read name
echo "Привет, $name!"
14.chmod +x greet.sh
./greet.sh
