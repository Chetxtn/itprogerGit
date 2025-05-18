# Модуль 5 – Контроль версій Git
# Виконання завдання до модуля

1. Ствоерння нового проєкту.
2. Виконуємо команду через **Git Bash** термінал і створюємо README.md для фіксації своїх дій!
> **Команда:**
> <br>git init
> <br>Відповідь: Initialized empty Git repository in D:/Development/Java/courses/itprogerGit/.git/

3. Налаштовуємо .gitignore
> .idea/
> <br>out/
> <br>!**/src/main/**/out/
> <br>!**/src/test/**/out/
> <br>bin/
> <br>admin/
> <br>config/
> <br>*.sass





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

8. Створюємо нову гілку
> **Команда:**
> <br>git branch blog

9. Переходимо в нову гілку і створюємо "папку blog з файлами: index.js, index.html;"
> **Команда:**
> <br>git switch blog

10. Зберігаємо стан цієї гілки
> **Команда:**
> <br>git add .
> <br>git commit -m "Create structure blog"

11. Повертаємося до основної гілки
> **Команда:**
> <br>git switch master

12. Додаємо нашу створену репозиторію на github
> **Команда:**
> <br>git remote add origin https://github.com/Chetxtn/itprogerGit.git

13. Відправляємо основну гілку в віддалену репо
> **Команда:**
> <br>git remote add origin https://github.com/Chetxtn/itprogerGit.git
