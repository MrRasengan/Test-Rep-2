# Test-Rep-1

## Hello Git!


УДАЛЕНИЕ СВЯЗИ С СКЛОНИРОВАННЫМ РЕПОЗИТОРИЕМ И УСТАНОВКА СВЯЗИ С НОВЫМ РЕПОЗИТОРИЕМ

PS C:\GIT\WorkGit\Test-Rep-1> git remote -v
origin  https://github.com/MrRasengan/Test-Rep-1.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-1.git (push)

PS C:\GIT\WorkGit\Test-Rep-1> git remote remove origin
PS C:\GIT\WorkGit\Test-Rep-1> git remote -v
PS C:\GIT\WorkGit\Test-Rep-1> git remote add origin https://github.com/MrRasengan/Test-Rep-2.git
PS C:\GIT\WorkGit\Test-Rep-1> git remote -v
origin  https://github.com/MrRasengan/Test-Rep-2.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-2.git (push)

PS C:\GIT\WorkGit\Test-Rep-1> git remote add source https://github.com/MrRasengan/Test-Rep-1.git
PS C:\GIT\WorkGit\Test-Rep-1> git remote -v
origin  https://github.com/MrRasengan/Test-Rep-2.git (fetch)
origin  https://github.com/MrRasengan/Test-Rep-2.git (push)
source  https://github.com/MrRasengan/Test-Rep-1.git (fetch)
source  https://github.com/MrRasengan/Test-Rep-1.git (push)
PS C:\GIT\WorkGit\Test-Rep-1>
