# Задание на верстку Главной страницы сайта

## Установка 
1. [Скачать](https://git-scm.com/download/win) и установить Git
2. [Скачать](https://github.com/coreybutler/nvm-windows/releases/download/1.1.9/nvm-setup.exe) и установить Node Virtual Environment (NVM)
3. Скачать Node версии 16.4.2 - в командном окне(cmd.exe) выполнить команду `nvm install v16.14.2`
4. Указать скаченную версию Node как текущую - в командном окне(__с правами Администратора__) выполнить команду `nvm use 16.14.2`
5. Склонировать проект задания(Проект) - в командном окне с правами пользователя выполнить команду `git clone https://github.com/jigius/tpl-main-page.git` в текущую папку
6. Перейти в папку Проекта - команда `cd tpl-main-page`
7. Установить все библиотеки Проекта - команда `npm install`
8. Сборка Проекта - команда `npm run build`

## Варианты выполнения задания

### Начальный уровень 
После успешной сборки появится файл Главной страницы `dist/index.html`, которую можно открыть в броузере. Главная 
страница содержит шаблон который сгенерирован фреймворком (Opencart) для сайта проекта. Данную страницу можно 
использовать как референс для выполнения задачи. 

Успешным результатом является сверстанная Главная страница со всеми ассетсами, удовлетворяющая требованиям ТЗ.
Результат предоставляется упакованным в ZIP-архив, который должен содержать все необходимые файлы для успешного 
открытия в броузере сверстаной страницы.   

### Продвинутый уровень
Требуется форкнуть и склонировать проект задания. После этого можно непосредственно править шаблон и ассетсы страницы.
В процессе работы над задачей, удобно использовать автоматическую сборку с включенным режимом разработки.

Исходники (шаблон страницы и ассетсы) находятся в папке `/src`.

Режим разработки запускается командой `npm run start`. В этом режиме запускается http-сервер(порт 8080) и открывается
броузер. При внесении правок, в автоматическом режиме пересобирается проект и обновляется страница в
броузере.

Успешным результатом является сверстанная Главная страница со всеми ассетсами, удовлетворяющая требованиям ТЗ.
Результат предоставляется в виде пулл-реквеста в оригинальный проект. 
