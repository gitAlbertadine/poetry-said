# poetry
```
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | /home/admin/.pyenv/versions/3.10.1/bin/python -
#ubuntu: export PATH='$PATH:/bin:/usr/bin:$HOME/.poetry/bin'
#termux: export PATH="$HOME/.poetry/bin:$PATH"
#source ...
#poetry config --list
#poetry self update
#poetry new package
#poetry new project --name package
poetry new --src package
cd package
poetry env use /home/admin/.pyenv/versions/3.10.1/bin/python
poetry install
#-existed project
#poetry init
poetry add django
#poetry add -D ...
#poetry remove -D pytest
poetry show --tree
poetry shell
django-admin startproject bookr .
python manage.py runserver
python manage.py startapp reviews
mm
m
sqlite3 mydatabase.db




```
