 # Инструкция для работы с Git и удалёнными репозиториями.

***Что такое Git?*** 
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

***Подготовка репозитория.***
Для создание репозитория необходимо выполнить команду ***git init***  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

# **Создание коммитов.**

***Git add.***
Для добавления измений в коммит используется команда ***git add***. Чтобы использовать команду ***git add*** напишите  ***git add <имя файла>*.***

***Просмотр состояния репозитория.***
Для того, чтобы посмотреть состояние репозитория используется команда ***git status***. Для этого необходимо в папке с репозиторием написать ***git status***, и Вы увидите были ли измения в файлах, или их не было.

***Создание коммитов.***
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду ***git commit***. Выполняется она так: ***git commit -m "<сообщение к коммиту>***. Все файлы для коммита должны быть **ДОБАВЛЕНЫ** и сообщение к коммиту писать **ОБЯЗАТЕЛЬНО**.

***Перемещение между сохранениями.***
Для того, чтобы перемещаться между коммитами, используется команда ***git checkout***. Используется она в папке с пепозиторием следующим образом: ***git checkout <номер коммита>***.

***Журнал изменений.***
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда ***git log***. Для этого достаточно выполнить команду ***git log*** в папке с репозиторием


# **Ветки в Git.**

***Создание ветки.***
Для того, чтобы создать ветку, используется команда ***git branch***. Делается это следующим образом в папке с репозиторием: ***git branch <название новой ветки>***.

***Слияние веток.***
Для того чтобы дабавить ветку в текущую ветку используется команда ***git merge <name branch>***.

***Удаление веток.***
Для удаления ветки ввести команду ***"git branch -d 'name branch'"***.

---
# **Добавление картинок.**
Для того что бы добавить ***картинку***, нужно :
![Картинка](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/1280px-Git-logo.svg.png) 

# **Добавление ссылки.**
Для того что бы добавить ***ссылку***, нужно:
[Работа с языком](https://lifehacker.ru/chto-takoe-markdown/)

# **Добавление цитат.**
Для того что бы добавить ***цитату***, нужно:
* Указать
+ символы
- Плюс, звездочка или минус

Чтобы добавить ***одиночную*** цитату надо поставить знак ">":
> The sun goes down, I feel the light betray me.

Чтобы добавить ***цитату с цитатой***, нужно поставить знак ">>" :
>You like to think you're never wrong.
>>You live what you've learned.
>>> Linkin Park.
---
# **Оформление списков и текста.**
***Шритфы.***
1. "#" - Заголовок.
2. "*  *" - Курсив.
3. "**  **" - Жирный шрифт.

***Ненумерованные*** :

+ Плюс.
+ Пробел.
+ "Текст".

*Либо.*

* Звездочка.
* Пробел.
* "Текст".

**Либо так.**

- Минус.
- Пробел.
- "Текст".

***Нумерованные***:

1. Один.
2. Два.
3. Три.

---
?