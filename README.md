#Awesome Node-webkit application

Тут детально описаны инструкции для построения node-webkit приложения в винде.
1. Если нет гита, то для начала [Скачиваем гит для винды](https://msysgit.github.io/), конечно же консольную версию.

2. Если нет nodejs, то [скачиваем](http://nodejs.org/)

3. В качестве сборщика используем Grunt-cli, установить который можно по ссылке: 
>npm i -g grunt-cli

5. После этого переходим в папку с проектом и выполняем команду: 
>npm i

5. Создаем файлы ```package.json``` и ```Gruntfile.js```. Их содержание смотрим в репозитории.

6. Для построения приложения используем Grunt командой:
>grunt nodewebkit

===
