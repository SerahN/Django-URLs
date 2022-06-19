# Django-URLs

This is a task given by I4GxZuri.
It tests urls on django.

A typical url configuration looks like this:

"""mysite URL Configuration

[...]
"""
from django.contrib import admin
from django.urls import path

urlpatterns = [
path('admin/', admin.site.urls),
]

This can then be modified.
