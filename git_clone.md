[< содержанию](./readme.md)

## <center> _Создание копии (удаленного) репозитария_ (***git clone***) </center>

Для начала работы с центральным репозитарием, следует создать копию
оригинального проекта со всей его историей локально:

***git clone /home/username/project myrepo*** — клонируем репозитарий с той же машины в директорию ***myrepo***.

***git clone ssh://user@somehost:port/~user/repository*** — клонируем репозитарий,
используя безопасный протокол ***ssh*** (для чего требуется завести у себя на машине aккаунт ***ssh***).

***git clone git://user@somehost:port/~user/repository/project.git/*** — у ***git*** имеется и собственный протокол.

Источник: https://habr.com/ru/post/60347/