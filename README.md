# Домашнее задание к занятию "`GitLab`" - `Дедюрин Денис`

---

## Задание 1
### Устанавливаем ВМ спомощью Vagrant-файла, регистрируем и запускаем Runner:

<img src = "img/git01.png" width = 100%>

---

## Задание 2

### Клонируем репозиторий с GitHub и пушим его к себе, в локальный GitLab:

<img src = "img/git02.png" width = 100%>

### Команды:
```
git clone https://github.com/netology-code/sdvps-materials.git dedyurind
cd dedyurindn/
git remote -v
git remote add dedyurindn http://gitlab.localdomain/netology/dedyurindn.git
git push dedyurindn
```

### Настраиваем pipeline и запускаем:
<img src = "img/git03.png" width = 100%>

### Файл .gitlab-ci.yml
<img src = "img/git06.png" width = 100%>
<img src = "img/git04.png" width = 100%>

### Результаты сборки:
<img src = "img/git05.png" width = 100%>