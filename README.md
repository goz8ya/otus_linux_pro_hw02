# ** Домашнее задание
Первые шаги с Ansible

Цель:
Написать первые шаги с Ansible.


Описание/Пошаговая инструкция выполнения домашнего задания:
Для выполнения домашнего задания используйте методичку
Ссылка на Vgrantfile

Что нужно сделать?

Подготовить стенд на Vagrant как минимум с одним сервером. На этом сервере используя Ansible необходимо развернуть nginx со следующими условиями:

необходимо использовать модуль yum/apt;
конфигурационные файлы должны быть взяты из шаблона jinja2 с перемененными;
после установки nginx должен быть в режиме enabled в systemd;
должен быть использован notify для старта nginx после установки;
сайт должен слушать на нестандартном порту - 8080, для этого использовать переменные в Ansible.

В чат ДЗ отправьте ссылку на ваш git-репозиторий. Обычно мы проверяем ДЗ в течение 48 часов.

Если возникнут вопросы, обращайтесь к студентам, преподавателям и наставникам в канал группы в Telegram.

Удачи при выполнении!

Критерии оценки:
Статус "Принято" ставится, если:

предоставлен Vagrantfile и готовый playbook/роль (инструкция по запуску стенда, если посчитаете необходимым);
после запуска стенда nginx доступен на порту 8080;
при написании playbook/роли соблюдены перечисленные в задании условия.
 