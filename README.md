# GeekBrainsLesson3

# Работа с Git (локальный репозиторий)

**git init**-инициализация локального репозитория

**git status**-получить информацию от Git о его текущем состоянии

**git add**- добавить файл или файлы к следующему коммиту

**git commit -m "message"**- создание коммита

**git log**-вывод на экран истории всех коммитов с их хэш-кодами

**git branch** - отображение всех веток

*данная команда отображает все существующие ветки, которые уже созданы; зеленым отмечена ветка, на которой мы находимся в настоящий момент*


**git branch branch_name**- создание новой ветки

*данная команда позволяет создать новую ветку с названием branch_name*


**git branch -d branch_name** - удаление уже слитой ветки

*необходимо для удаление ветки, которая уже слита с веткой master*


**git branch -D branch_name**- удаление ещё не слитой ветки

*если ветка ещё не слита, но её необходимо удалить, то используется заглавная D*


**git checkout branch_name** - переход на другую ветку

*необходимо обращать особое внимание на то, в какой ветке осуществляются изменения, чтобы не затронуть основную ветку; не забывать переходить на master после окончания работы с доп. веткой*


**git checkout -b branch_name** - создание ветки branch_name и переход в неё


**git merge branch_name**- происходит слияние веток

*в ветку, на которой мы находимся, сливается ветка branch_name*

# Работа с ГитХаб (удаленный репозиторий): #

**git clone *ссылка*** - создание локальной копии удаленного репозитория

**git push** - отправление изменений в удалённый репозиторий

**git pull** - "выкачивание" всех изменений из удаленного репозитория на свой компьютер

1. **Не гитовские команды:**

**cd** ..(уровень выше) или folder_name(уровень ниже) - перемещение между уровнями папок

**ls** - команда, отображающая файлы, находящиеся в папке

2. **На самом ГитХабе**

**fork** - "вилка", своя отдельная копия репозиторя на сайте

**PullRequest** - запрос на слитие своих коммитов с "родителем" репозитория