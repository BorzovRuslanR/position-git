# Памятка Git + Github

## Проверка на наличие .git

`$ ls -la`

## Инициализация git (если нет .git)

`$ git init`

## В случае промаха папки, удалить .git

`$ rm -rf .git/`

## Индексация файлов перед коммитом

`$ git add .`

## Проверить статус репозитория

`$ git status`

## Проверить git пользователя 

`$ git config --list | grep user`

## Меняем конфигурацию на себя

`$ git config --global user.name "Borzov Ruslan"`
`$ git config --global user.email menejer.r@yandex.com`


## Сохраняем изменения в истории git

`$ git commit -m "Commit description"`

## Посмотреть историю коммитов

`$ git log`

## Проверить наличие удалённого репозитория (Github)

`git remote show origin`

## Можно удалить origin

`$ git remote rm origin`

## Добавить удалённый репозиторий 

`$ git remote add origin https://github.com/username/repository_name.git`

## Отправляем данные на репозиторий на (Github)

`$ git push origin master`



