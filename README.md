Moja utworzona strona pod adresem:
http://kinia0o.pythonanywhere.com/

Wykonane kroki:

<br />Utworzenie środowiska o nazwie env_22677:
<br />python -m venv env_22677 
<br />Aktywacja środowiska:
<br />env_22677\Scripts\activate 
<br />Instalacja Django:
<br />pip install -r requirements.txt <br />
![djangoinst](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/fce05d59-144f-4fec-ba70-06e8fac76c03) <br />
<br />Utworzenie projektu strony:
<br />django-admin.exe startproject strona22677 .
<br />Utworzenie bazy danych dla strony:
<br />python manage.py migrate<br />
![baza](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/24e11cc9-a803-47eb-ab2b-0e8a2bf769b0)

<br />Uruchomienie serwera:
<br />python manage.py runserver
<br />Utworzenie aplikacji wewnątrz projektu:
<br />python manage.py startapp blog22677
<br />Dodanie modelu do bazy danych:
<br />python manage.py makemigrations blog22677
<br />Dodanie konta administratora:
<br />python manage.py createsuperuser<br />
![uzytkownik](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/1f8a3a1c-e8b3-40c2-965c-fdef53f8a4c6)

<br />Utworzenie repozytorium git i pierwsze przesłanie kodu na Github::
<br />git init
<br />git config --global user.name "kinia0o"
<br />git config --global user.email kinia0o@wp.pl
<br />git add --all .
<br />git commit -m "pierwszy commit django"
<br />git remote add origin https://github.com/kinia0o/my-first-blog-22677.git
<br />git push -u origin master

<br />W PythonAnywhere bash:
<br />Zainstalowanie pomocniczego narzędzia do ściągnięcia kodu z GitHuba:
<br />pip3.6 install --user pythonanywhere
<br />Uruchamienie pomocnika, aby automatycznie skonfigurować aplikację z GitHubem
<br />pa_autoconfigure_django.py https://github.com/kinia0o/my-first-blog-22677.git
![where1](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/639af999-d835-4762-afce-0be6bc0d1470)

<br />Dodanie super użytkownika:
<br />python manage.py createsuperuser
<br />Do pobrania kodu z Githuba:
<br />git pull <br />
![gitpull](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/e3fbcc93-31cd-4633-aee6-7f08a5b88d6f)
<br />Wyświetlenie nowej zawartości kodu:
<br />https://www.pythonanywhere.com/ > Web > Reload
![reload](https://github.com/kinia0o/my-first-blog-22677/assets/23746874/00e45c9d-6568-41af-b986-4b4001694b36)



