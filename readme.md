 # **Инструкция по работе с GIT 🛠**
License [MIT](./License.md)

![git-logo](./img/git-logo.png)

---

### **Содержание**:
1. [*Что такое Git.*](./Git.md)
2. [*Что такое репозиторий?*](./repository.md)
3. [*Работа с локальным репозитарием.*](./rlr.md) 
   1.  [*Команда настройки параметров для Git на вашем компьютере*(___git config___)](./git_config.md)
   2. [*Как создать репозитарий?*(***git init***)](./git_init.md)
   3. [*Как сделать индексацию изменений?*(***git add и git rm***)](./git_add_i_git_rm.md)
   4. [*Cостояние проекта, измененные и не добавленные файлы, индексированные файлы*.(***git status***)](./git_status.md)
   5. [*Что такое коммиты?*(***git commit***)](./commit.md)
   6. [*Возврат к определенному коммиту, откат изменений, «жесткий» или «мягкий»*(***git reset***)](./git_reset.md)
   7. [*Отмена изменений, произведенных в прошлом отдельным коммитом*(***git revert***)](./git_revert.md)
   8. [*Разнообразная информация о коммитах в целом, по отдельным файлам и различной глубины погружения в историю*(***git log***)](./git_log.md)
   9. [*Отличия между деревьями проекта; коммитами; состоянием индекса и каким-либо коммитом.*(***git diff***)](./git_diff.md)
   10. [*Как показать изменения, внесенные отдельным коммитом?*(***git show***)](./git_show.md)
   11. [*Вспомогательные команды, помогающие отслеживать изменения файов.*(***git blame и git annotate***)](./git_blame_i_git_annotate.md)
   12. [*Поиск слов по проекту, состоянию проекта в прошлом.*(***git grep***)](./git_grep.md)
4. [*Ветвление.*](./branching.md)
   1. [*Cоздание, перечисление и удаление веток*(___git branch___)](./git_branch.md)
   2. [*Переключение между ветками, извлечение отдельных файлов из истории коммитов*(***git checkout***)](./git_checkout.md)
   3. [*Слияние веток (разрешение возможных конфликтов).*(***git merge***)](./git_merge.md)
   4. *[Построение ровной линии коммитов*(___git rebase___)](./git_rebase.md)
   5. [*Применение к дереву проекта изменений, внесенных отдельным коммитом*(***git cherry-pick***)](./git_cherry_pick.md)
5. [*Прочие команды и необходимые возможности*](./other_commands.md)
   1. [*Хэш — уникальная идентификация объектов*](./hash.md)
   2. [*Тэги как способ пометить уникальный коммит*(___git tag___)](./git_tag.md)
   3. [*Относительная адресация*](./relative_addressing.md)
   4. [*Файл ***.gitignore*** — объясняем git, какие файлы следует игнорировать*](./gitignore.md)
6. [*Основы работы с удаленным репозитарием*](./bowwarr.md)
   1. [*Удаленные ветки (remote tracking branches)*](./rtb.md)
   2. [_Создание копии (удаленного) репозитария_(***git clone***)](./git_clone.md)
   3. [*Забираем изменения из центрального репозитария (из удаленной ветки)*(***git fetch и git pull***)](./git_fetch_git_pull.md)
   3. [*Вносим изменения в удаленный репозитарий (удаленную ветку)*(***git push***)](./git_push.md)
7. [*git-о-день*](./git_o_day.md)
   1. [*Обычный workflow при работе с локальным репозитарием*](./workflow_1.md)
   2. [*Workflow при работе с удаленным репозитарием*](./workflow_2.md)
8. [*Заключение*](./conclusion.md)

---

GIT logo by Jason Long. http://git-scm.com/downloads/logos, license: [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/)