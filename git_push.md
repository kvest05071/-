[< содержанию](./readme.md)

После проведения работы в экспериментальной ветке, слияния с основной,
необходимо обновить удаленный репозитарий (удаленную ветку). Для этого
используется команда git push:

git push — отправить свои изменения в удаленную ветку, созданную при
клонировании по умолчанию.

git push ssh://yourserver.com/~you/proj.git master:experimental — отправить изменения
из ветки master в ветку experimental удаленного репозитария.

git push origin :experimental — в удаленном репозитарии origin удалить ветку experimental.

git push origin master:master — в удаленную ветку master репозитария origin (синоним
репозитария по умолчанию) ветки локальной ветки master.

Источник: https://habr.com/ru/post/60347/