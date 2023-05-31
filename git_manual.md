# Основные комманды Git. Cеминар №1

- Для оформления с помощью Markdown пользовался [GitHub](https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

![Логотип Гит](logo_git.jpg) ![VS Code](/vslogo.jpg)

>*git init* – инициализация локального репозитория

>*git status* – получить информацию от git о его текущем состоянии

>*git add* – добавить файл или файлы к следующему коммиту

>*git commit -m "текст комментария"* – создание коммита

>*git log* – вывод на экран истории всех коммитов с их хеш-кодами

>*git checkout* – переход от одного коммита к другому

>*git checkout master* – вернуться к актуальному состоянию и продолжить работу

>*git diff* – увидеть разницу между текущим файлом и закоммиченным файлом

# Основные комманды Git. Семинар №2

> *git branch [branch_name]* - создать новую ветку с названием branch_name.

> *git checkout [branch_name]* - переход к ветке с имененем branch_name.

> *git branch* - выводит список веток и указывает текущую ветку

> *git branch -d [branch_name]* - **удaлить** ветку с названием branch_name

> *git log --graph* - выводит историю коммитов и их хеш-коды в древовидной форме

> *git log --oneline* - выводит построчно коммиты и хеш-коды

> *git merge [branch_name]* - выполняет слияние ветки [branch_name] с текущей веткой

> *git merge --abort* - отменяет слияние веток, в котором происходит конфликт

> *git checkout -b [branch_name] - содает новую ветку с имененем branch_name и переходит на нее.

> *git commit -am "message text"* - создает коммит к отслеживаемому файлу.