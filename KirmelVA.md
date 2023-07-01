# Инструкция по работе с Git
## Основные понятия
! Git — самая популярная система контроля версий, но не единственная. Алгоритм работы подобных систем схож
## 1.Команды:
* git add - добавляет файл
* git commit - зафиксировать или сохранить
* git log - Журнал изменений
* git checkout - Переключение между версиями
* git init - Инициализация: указываем папку, в которой git начнёт отслеживать изменения
* git status - Показывает текущее состояние гита, есть ли изменения, которые нужно сохранить
* git checkout master - вернуться в тот коммит, где работаем
* git diff - Показывает разницу между текущим файлом и сохранённым
## 2.Ветки
* git branch - выводит список веток
* git branch branch_name - создает новую ветку с именем branch_name
* git merge - слияние веток
# Удаленный репозиторий
## Основные моменты
### Команды:
* git clone - Эта команда позволяет склонировать внешний репозиторий на наш ПК
* git pull - Эта команда позволяет скачать все из текущего репозитория и автоматически 
сделать merge с нашей версией 
* git push - эта команда позволяет отправить нашу версию репозитория на внешний 
репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории 
## Как сделать pull request?
* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория 
* Создаем новую ветку и в НЕЕ вносим свои изменения 
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request