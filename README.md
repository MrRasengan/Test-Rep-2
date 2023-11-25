# Test-Rep-1

Rep 2
Conflict fgdthye
Conflict figdfg

## Hello Git!


УДАЛЕНИЕ СВЯЗИ С СКЛОНИРОВАННЫМ РЕПОЗИТОРИЕМ И УСТАНОВКА СВЯЗИ С НОВЫМ РЕПОЗИТОРИЕМ

git remote -v
origin  https://github.com/MrRasengan/Test-Rep-1.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-1.git (push)

git remote remove origin
git remote -v
git remote add origin https://github.com/MrRasengan/Test-Rep-2.git
git remote -v
origin  https://github.com/MrRasengan/Test-Rep-2.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-2.git (push)

git remote add source https://github.com/MrRasengan/Test-Rep-1.git
git remote -v
origin  https://github.com/MrRasengan/Test-Rep-2.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-2.git (push)
source  https://github.com/MrRasengan/Test-Rep-1.git (fetch)
source  https://github.com/MrRasengan/Test-Rep-1.git (push)


git fetch --all   Скачали изменения с удалённого репозитория

git log origin/main ^main     Показывает последние коммиты в ветке

git merge source/main
git merge origin/main
