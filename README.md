# Домашнее задание к занятию 15.2 "`Основы Git`" - `Маховский Виктор`

### Задание 1. Знакомимся с GitLab и Bitbucket

---

`Код:`
```
cd /netology/devops-netology/
git remote add gitlab git@gitlab.com:devops-mbrhard/devops-netology.git
git push -u gitlab main
git remote -v
```

![Task 15-2-1-1](img/HW-15-2-1-1.png)

![Task 15-2-1-2](img/HW-15-2-1-2.png)


---

### Задание 2. Теги

---

`Код:`
```
cd /netology/devops-netology/
git tag v0.0
git tag -l
git remote -v
git push --tags origin
git push --tags gitlab

git tag -a v0.1 -m "v0.1"
git push --tags origin
git push --tags gitlab
```

![Task 15-2-2-1](img/HW-15-2-2-1.png)

![Task 15-2-2-2](img/HW-15-2-2-2.png)

![Task 15-2-2-3](img/HW-15-2-2-3.png)

![Task 15-2-2-4](img/HW-15-2-2-4.png)

---


### Задание 3. Ветки

---

`Код:`
```
cd /netology/devops-netology/
git checkout main
git log --oneline --all
git checkout df54266
git switch -c fix
git push -u origin fix

git add README.md
git commit -m "Add info from fix branch"
git push origin fix
git log --oneline --all --graph
```

![Task 15-2-3-1](img/HW-15-2-3-1.png)

![Task 15-2-3-2](img/HW-15-2-3-2.png)

![Task 15-2-3-3](img/HW-15-2-3-3.png)

---

### Задание 4. Упрощаем себе жизнь

---

Жизнь пока не упростил, так как работаю в Visual Studio Code. Но для него есть расширения, попробую поставить.

На репозиторий в GitHub: https://github.com/mbrhard-devops/devops-netology

На репозиторий в GitLab: https://gitlab.com/devops-mbrhard/devops-netology

---