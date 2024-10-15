crie ambiente virtual: " python3 -m venv meu_ambiente_virtual "

entre no ambiente virtual: " source meu_ambiente_virtual/bin/activate "

atualize o pip: " pip install --upgrade pip "
instale o django " pip install django "

inicie o django " django-admin startproject mysite "

entre na pasta mysite " cd mysite "

criar nosso app django propriamente dito " django-admin startapp myapp "

agora, se dirija até a pasta mysite, mysite, settings.py e digite em INSTALLED_APPS = [ "myapp", ]

faça as migrações pendentes com " python manage.py migrate "

faça o server rodar com " python manage.py runserver "

devera aparecer uma tela com: The install worked successfully! Congratulations! You are seeing this page because DEBUG=True is in your settings file and you have not configured any URLs.