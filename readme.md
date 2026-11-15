# ЗОС: Linux security

Уникальный номер: 374991
GitHub: alexeybulbas-zos

## Выполненные проверки

1: UID 1234, группа students, пароль 90 дней.
2: поиск файлов set-UID и процессов с EUID 0.
3: чтение закрытого root-файла копией cat.
4: смена владельца с CAP_CHOWN.
5: правило sudo для timedatectl set-time.
6: скриншот, история и файлы результатов.

## Артефакты

mephi-screenshot.png, history.out, stat.out, getcap.out,
suid-files.out, privileged-processes.out, passwd.out,
shadow.out, group.out, sudoers.out, sudoers-user1-time.out
