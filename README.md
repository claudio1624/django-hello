
PASO 1.
	Ingresamos   ->   https://docs.djangoproject.com/en/2.0/howto/windows/

PASO 2.
	Ingresamos don dice
	About pip    ->   https://pip.pypa.io/en/latest/installing/

PASO 3.
	Intalcion con get-pip.py ->    https://bootstrap.pypa.io/get-pip.py
	los abrira un archivo    ->    Lo guardamos como get-pip.py en un pcarpeta creada python

PASO 4.	
	En la consola instalamos pip
	python get-pip.py   ->  (C:\Users\csip\Desktop\Python\Django>python get-pip.py)
	
PASO 5.
	En la consola abrimos el directorio indicado c:Python 27/scripts
	Intalamos  -> pip install virtualenv   (C:\Python27\Scripts>pip install virtualenv)

PASO 6.
	pip search python   ->  (C:\Python27\Scripts>pip search python)
	pip search django   ->  (C:\Python27\Scripts>pip search django)

PASO 7.
	instalamos Django
	-m pip install -U pip  ->   (C:\Python27\Scripts>python -m pip install -U pip)

PASO 8
	Ejecutamos virtualenv
	virtualenv .    ->  (C:\Python27\Scripts>virtualenv .)

PASO 9.
	Buscamos dentro de estas carpetas conde tenemos Activate y Deactivate

PASo 10.
	Eecutamos -> C:\Python27\Scripts\Scripts>activate.bat
	los mostrara donde teneos instalado el local   ->   (Scripts) C:\Python27\Scripts\Scripts>

PASO 11.
	Instalamos pip install django
	(Scripts) C:\Python27\Scripts\Scripts>pip install django
	
PASO 12.
	Instalamos   
	django-admin.py startproject mysite .   ->  ((Scripts) C:\Python27\Scripts\Scripts>django-admin startproject mysite .)
	Nos creara el direectorio mysite

PASO 13.
	python manage.py runserver ->  (Scripts) C:\Python27\Scripts\Scripts>python manage.py runserver
	ingresamos a la direcion indicada  (  ---- http://127.0.0.1:8000/---  )
		contenttypes, sessions.
		Run 'python manage.py migrate' to apply them.
		July 07, 2018 - 12:19:04
		Django version 1.11.14, using settings 'mysite.settings'
		Starting development server at http://127.0.0.1:8000/
		Quit the server with CTRL-BREAK.

	
	**Control + C    ->    matamos el proceso de servidr web