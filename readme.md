# Инструкция для работы с Git и удалёнными репозиториями
Добавим некоторый текст, который должен привести к конфликту при слиянии веток!!!
**Все происходящее должно привести к конфликту веток!!!**
## Что такое Git?

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория

Для создание репозитория необходимо выполнить команду _git init_ в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add

Для добавления измений в коммит используется команда _git add_. Чтобы использовать команду _git add_ напишите _git add <имя файла>_

### Просмотр состояния репозитория

Для того, чтобы посмотреть состояние репозитория используется команда _git status_. Для этого необходимо в папке с репозиторием написать _git status_, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду _git commit_. Выполняется она так: _git commit -m "<сообщение к коммиту>_. Все файлы для коммита должны быть **_ДОБАВЛЕНЫ_** и сообщение к коммиту писать **_ОБЯЗАТЕЛЬНО_**.

## Перемещение между сохранениями

Для того, чтобы перемещаться между коммитами, используется команда _git checkout_. Используется она в папке с пепозиторием следующим образом: _git checkout <номер коммита>_

## Журнал изменений

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда _git log_. Для этого достаточно выполнить команду _git log_ в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда _git branch_. Делается это следующим образом в папке с репозиторием: _git branch <название новой ветки>_

## Слияние веток

_Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*_ - сделал курсивом

## Удаление веток

**Для удаления ветки ввести команду "git branch -d 'name branch'"** - сделал жирным.

- Первый элемент
- Второй элемент
- Третий элемент

1. Первый пункт
2. Второй пункт
3. Третий пункт

hello world!!!

![тут был котик](https://mobimg.b-cdn.net/v3/fetch/4d/4d671cfe78cbb63a617875e1f6023157.jpeg?h=600&r=0.5)

Внесение изменений во вторую ветку!!!
Внесение изменений в третью ветку!!!
Внесение изменений в четвертую ветку!!!
Вносим изменения в первую ветку!!!