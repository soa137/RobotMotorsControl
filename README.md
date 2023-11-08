# Общее описание проекта RobotMotorsControl:
## Управление двигателями робота
## Описание работы с Git:
- Создал репозиторий RobotMotorsControl на github и сделал его public, затем клонировал его на локальный компьютер с помощью команды `git clone https://github.com/soa137/RobotMotorsControl.git`
- Создал файлы в каталоге репозитория README.md и motors_control.py и добавил командой `git add README.md` и `git add motors_control.py` и зафиксировал командой `git commit -m "Добавил файлы README.md и motors_control.py"`
- Отправил изменения командой `git push`
- Создал новую ветку для изменения функции плавного изменения скорости в файле motors_control.py командой `git checkout -b new_branch_robot`
- Добавил изменения командой `git add motors_control.py` и зафиксировал командой `git commit -m "Изменил функцию плавного изменения скорости в файле motors_control.py"`
- Отправил изменения командой `git push --set-upstream origin new_branch_robot`
- Затем переключился на основную ветку командой `git checkout master` и сделал слияние веток командой `git merge new_branch_robot`
- Убедился что нет конфликтов, проверил статус командой `git status`
- Отправил изменения командой `git push`
