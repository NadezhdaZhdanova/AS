# AS
## Версии

cat /etc/astra/build_version

uname –a     версия ядра

sudo astra-modeswitch get         режим работы в цфирафх

sudo astra-modeswitch list        соответсвие режимов в цифрах буквам

## Обновления

sudo apt update

sudo astra-update -A –r          перед стартом обновления отключает механизмы обеспечения безопасности

sudo apt dist-upgrade            Дебиан команда

## SSH

ssh ip-адрес -l login

## misc

sudo -i режим суперпользователя

pstree -u  показывает дерево процессов

ps aux   процессы с пользователем

pdp-ls -M /etc/fstab  смотреть мандатные атрибуты файла



