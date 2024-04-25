# Список корисних команд для роботи з Git

1. git clone - копіює репозиторій (папку з файлами) на комп'ютер
2. git branch 'branchName' - створює гілку з назвою 'branchName'
3. git checkout 'branchName' - переходить на гілку 'branchName'
4. git checkout -b 'branchName' - створює гілку 'branchName' і переходить на неї
5. git add . - зберігаємо зміни в файлах
6. git commit -m 'commit message' - підписуємо збережені зміни в файлах
7. git push - відправляємо зміни на GitHub
8. git pull - отримуємо останні зміни з сайту GitHub
9. git status - показуємо статус проекту
10. git branch - показуємо список гілок в проекті
11. git branch -r - показуємо список гілок на сайті GitHub
12. git branch -a - показуємо список гілок на комп'ютері та на сайті GitHub
13. git fetch - отримуємо зміни з сайту GitHub
14. git stash - зберігаємо не збережені зміни і кладемо їх в буфер обміну
15. git stash apply - вставляємо збережені зміни в буфер обміну
16. git merge 'branchName' - зливаємо гілку з назвою 'branchName' в поточну
17. git merge --abort - відміняємо зливання гілок
18. git branch -d 'branchName' - видаляє гілку локально
19. git push origin --delete 'branchName' - видаляє гілку з сайту GitHub
20. git diff - показує відрізки рядків між двома версіями файлу (між двома комітами)
21. git log - показує історію комітів

> Для виходу з режиму перегдялу 'q'

### Alias

1. git config --get-regex alias - подивитися всі alias
2. git config alias.'aliasName' - подивитися яку команду має 'aliasName'
3. git config --global alias.co checkout - додати новий alias
4. git config --global alias.co commit - змінити вже існуючий
