                               view.py
--------------------------------------------------------------------------------

from django.shortcuts import render
from django.http import HttpResponse

# Create your views here.


def home(request):
    return render(request, 'home.html', {'name': 'Navin'})


def add(request):

    val1 = int(request.GET['num1'])
    val2 = int(request.GET['num2'])
    res = val1 + val2

    return render(request, "result.html", {'result': res})


--------------------------------------------------------------------------------
                              home.html
--------------------------------------------------------------------------------

{% extends 'base.html' %}

{% block content %}
<h1>Hello {{name}}!!!!!</h1>

<form action="add">

    Enter 1st number : <input type="text" name="num1"><br>
    Enter 2st number : <input type="text" name="num2"><br>
    <input type="submit">

</form>

{% endblock%}


--------------------------------------------------------------------------------
                              result.html
--------------------------------------------------------------------------------

{% extends 'base.html' %}

{% block content %}

Result : {{result}}

{% endblock%}

--------------------------------------------------------------------------------
                              base.html
--------------------------------------------------------------------------------

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Telusko</title>
</head>

<body bgcolor="cyan">

    {% block content %}

    {% endblock %}

</body>

</html>


--------------------------------------------------------------------------------
                              urls.py ::calc
--------------------------------------------------------------------------------

from django.urls import include, path
from . import views
from django.contrib import admin

urlpatterns = [
    path('', views.home, name='home'),
    path('add', views.add, name='add')

]

--------------------------------------------------------------------------------
                              urls.py ::telusko
--------------------------------------------------------------------------------

from django.contrib import admin
from django.urls import path, include

urlpatterns = [
    path('', include('calc.urls')),
    path('admin/', admin.site.urls),
]
