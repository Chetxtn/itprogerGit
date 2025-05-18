# Модуль 5 – Контроль версій Git
# Виконання завдання до модуля

1. Ствоерння нового проєкту.
2. Виконуємо команду через **Git Bash** термінал і створюємо README.md для фіксації своїх дій!

> git init<br>
> Відповідь: Initialized empty Git repository in D:/Development/Java/courses/itprogerGit/.git/

3. Налаштовуємо .gitignore

> .idea/
> <br>out/
> <br>!**/src/main/**/out/
> <br>!**/src/test/**/out/
> <br>bin/
> <br>itprogerGit.iml

4. Створюмо перші файли проєкту Main.java
5. Додаємо всі файли в локальне сховище
> **Команда:**
> <br>git add .
6. Перевірка статусу
> **Команда:**
> <br>git status

> Відповідь:
> <br>new file:   .gitignore
> <br>new file:   README.md
> <br>new file:   src/com/git/Main.java

7. Виконуємо commit
> **Команда:**
> <br>git commit -m "init project"

8. Переходимо до створення нової гілки
> **Команда:**
> <br>git status