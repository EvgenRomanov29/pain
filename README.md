# git-lesson-05-10

Hello world 


# Работа с удаленными репозиториями

## Команда git clone
Команда git clone позволяет копировать или клонировать к себе репозитории из интернета. Для этого мы обращаемся к программе Git, указываем параметр clone и после этого даём адрес того репозитория, который надо скачать. Далее в папке, где вызывается команда git clone, появляется новая папка. И уже внутри этой папки будет лежать полная копия указанного нами репозитория.
## Команда git pull
Эта команда позволяет скачать всё актуальное из нашего удалённого репозитория. Команда очень простая. Мы указываем программу git и параметр pull. Она позволяет получить из интернета актуальное состояние удалённого репозитория и скачать его на наш репозиторий. Обратите внимание, что pull — составная команда. Помимо выкачивания из интернета, она ещё и мержит, то есть сливает, изменения с нашими. Если возникают какие-то конфликты, то окошко будет таким же, как при конфликтах обычного git merge. То есть коменда состоит из двух частей: первая часть скачивает изменения с удалённого репозитория, а вторая — сливает эти изменения с текущим репозиторием.


рпрапр