                               view.py
--------------------------------------------------------------------------------

from django.shortcuts import render
from django.http import HttpResponse

# Create your views here.


def home(request):
    return render(request, 'home.html', {'name': 'Kiran'})


--------------------------------------------------------------------------------
                              home.html
--------------------------------------------------------------------------------

<h1>Hello {{name}}!!!!!</h1>


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

--------------------------------------------------------------------------------
                              settings.py 
--------------------------------------------------------------------------------

 'DIRS': [os.path.join(BASE_DIR, 'templates')],
