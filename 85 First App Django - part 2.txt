                               view.py
--------------------------------------------------------------------------------

from django.shortcuts import render
from django.http import HttpResponse

# Create your views here.


def home(request):
    return HttpResponse("Hello World")


--------------------------------------------------------------------------------
                              urls.py ::calc
--------------------------------------------------------------------------------

from django.urls import include, path
from . import views
from django.contrib import admin

urlpatterns = [
    path('', views.home, name='home'),

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