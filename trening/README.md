# Инструкция по установке и настройке Git

## Установка Git

### Если у вас Fedora, CentOS:
```sh
$ sudo dnf install git-all
# Установка логина
git config --global user.name "[name]"

# Установка email
git config --global user.email "[email address]"

# Подсветка вывода
git config --global color.ui auto

# Установка редактора по умолчанию
git config --global core.editor "[program]"

# Создать папку
mkdir [имя]

# Основные команды

mkdir [имя]

# Информация о файле HEAD в Git

Файл `HEAD` (голова, головной) указывает на последний коммит в системе Git. Файл `HEAD` находится в папке `.git`.

Для проверки содержимого файла `HEAD` можно использовать команду:
```sh
cat .git/HEAD


