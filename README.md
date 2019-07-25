Домашнее задание
Настраиваем бэкапы
Настроить стенд Vagrant с двумя виртуальными машинами server и client.

Настроить политику бэкапа директории /etc с клиента:
1) Полный бэкап - раз в день
2) Инкрементальный - каждые 10 минут
3) Дифференциальный - каждые 30 минут

Запустить систему на два часа. Для сдачи ДЗ приложить 
[list jobs](list_jobs.txt) 

[list files jobid](list_files_jobid.txt)

и сами конфиги bacula-*
[bacula-dir.conf](bacula-dir.conf)
[bacula-sd.conf](bacula-sd.conf)
[bacula-fd.conf](bacula-fd.conf)

* Настроить доп. Опции - сжатие, шифрование, дедупликация
