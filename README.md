# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
model.py
from django.contrib import admin
from django.db import models
class Books(models.Model):
    name=models.CharField(max_length=50);
    author=models.CharField(max_length=20);
    price=models.IntegerField();
    dateofpublication=models.DateField();
    genre=models.CharField(max_length=30);
    code=models.CharField(max_length=20,primary_key=True);
class bookAdmin(admin.ModelAdmin):
      list_display=("name","author","price","dateofpublication","genre","code");

admin.py
from django.contrib import admin
from .models import book,bookAdmin
admin.site.register(book,bookAdmin)

## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
