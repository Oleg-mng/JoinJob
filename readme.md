

# Начало

# вторая команда

Представляем список известных команд git 

## Начало работы

1. git init             # создать новый проект в текущей директории

2. git status              # показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)

3. git diff                # сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

4. 
- git add имя файла # добавить для отслеживания MD новый файл

- git add .        # добавить в индекс все новые, изменённые, удалённые файлы из текущей директории и её поддиректорий

5. 
- git commit -m "Name of commit"    # зафиксировать в коммите проиндексированные изменения (закоммитить), добавить сообщение
- git commit -a "Name of commit" # делает коммит бОльшего объема (несколько строк), доп команды shift i, пишем коммит, esc, shift :, wq, enter

6. git log    # просмотр состояния системы (записи всех актуальных комммитов)

7. .gitignore #  в этот файл можно выкладывать все что не хотим чтобы отслеживал git, например foto

8. ![название](имя файла)   # подгрузить изображения

9. clear    # очистить экран терминала (поднять текст вверх)

## Ветки

10. git branch                 # показать список веток
git branch new name                # создать новую ветку

11. git checkout имя (ветки или коммита)       # переход к ветке или коммиту

12. git merge имя ветки которую присоединяем   # позволяет слить/объединить 2 ветки между собой, находиться при этом нужно в той ветке к которой присоединяем

13. git checkout master   # возврат к последнему состоянию

14. git log --graph  # отображение дерева с ветками

## Работа с удаленным доступом github

15. fork   # делаем копию с чужого репозиторию. Далее подгружаем его в VSC через Source Control (кнопка clone remote...)

16. git clone https://github.com/cyberspacedk/Git-commands.git    # клонировать удаленный репозиторий в одноименную директорию

17. git cd # смена директории на актуальную для работы

18. git push  # синхронизируем данные с удаленным репозиторием на github

19. git pull  # если изменения сделаны на github, то выкачиваем их в локальный репозиторий

