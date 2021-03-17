# project
first project




mkdir - 
rm -            (rm -R)
touch - 
cd -             (cd .. / ..)
ls -         (-a)
cp -
mv - 
echo -          (echo >)
cat - 
clear - очистить окно.
git init- создать репозеторий
git status - статус репозитория
git remote -v  - проверка соединеия репозиториев
git remote add (name/url)- связь между локальным и удаленным репозеториями
git add <file> -  добавить файл к будущему коммиту
git commit - записать коммит (i - начать запись, Esc, затем :wq - для выхода и записи)

git commit -m'commit mesage' - записать комит с сообщением 
git rm --cached <file> - удалить коммит обьявленный в репозитории.
git restore <file> - отменить изменения в коммите
git commit -am 'text' - добавить коммит и подтверждение комита
 

.gitkeep - добавляется в пустую папку что бы ГИТ ее видел. 
.gitignore -  добавить файл, в него внести что игнорировать.

git log - история изменений (q - выход)
git log --oneline - история изменений построчно
git reset <hash commit> - удалить из истории коммит.вводить нужно хэш комита к котрому хочешь вернуться а не который хочешь удалить.
git reflog - история всех операций в репозитории.
git revert - отменяет, но не удаляет коммит.

git branch - просмотр ветки
git branch "name" - создание новой ветки "name"(ковычки не нужны).
git checkout name - перейти на ветку name.
git branch 'name' 'master' - создать ветку name с началом на ветке master.
git checkout -b 'name' - перейти на ветку name, и если ее нет то создать ее.

gir clone 'адрес с сайта''name dir' - перенос репа с сайта на пк в папку name dir.
git push - отправка файлов на сервер.
git push -u -отправка файлов с созданием ветки на сайт.
git pull -  скачать с сайта все изменения
git fetch - подгрузить обновления из репозетория

ssh-keygen - создает ssh ключ
 
