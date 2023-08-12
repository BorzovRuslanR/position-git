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

## Сохраняем изменения в истории git

`$ git commit -m "Commit description"`

## Посмотреть историю коммитов

`$ git log`

## Проверить git пользователя 

`$ git config --list | grep user`

## Меняем конфигурацию на себя

`$ git config --global user.name "Borzov Ruslan"`
`$ git config --global user.email menejer.r@yandex.com`

