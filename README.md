# for_gb_attestationGit
Прохожу последнее задание по контролю версий

Тут я буду писать как работать с удалленым репозиторием с предложнением pull request

1. Надо зайти на аккаун человека и найти репозиторий, которому вы хотите предложить pull request
2. Сделать fork этого репозитория, и он отобразиться у вас в аккаунте.
3. На своем уже аккаунте с *форкнутого* репозитория сделать копию: Code-> HTTPS-> copy code
4. Войти в визуал студио коде, после чего набрать команду 
```sh
git clone <adress_of_code>

```
5. он склонирует весь репозиторий на ваш локальный компьютер. После надо пройти в директорий:
```sh
dir <name_of_repository>
```
6. Пройти в него
```sh
cd <name_of_repository>

```

7. поднимитесь выше нынешнего рассположения в папке:
```sh
cd ...
```
8. создайте там папку с таким же названием как репозиторий
```sh
mkdir <name>
```
9. Пройдите в эту папку 
```sh
cd <name>
```
10. После следуйте рекомендациям с GitHub, тут в качестве примера название репозитория идет как proverka
```sh
echo "# proverka" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Telli-H/proverka.git
git push -u origin main
```

11. После создания новой ветки 
```sh
git branch new_branch
git checkout new_branch
```
зафиксировать (запушить) ветку поможет 
```sh
git push --set-upstream origin new_branch
```
после этого ваша новая ветка будет на сервере GitHub

контратака конфликту, пишу это с визуал студио код


