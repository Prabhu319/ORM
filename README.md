# Ex02 Django ORM Web Application
# Date:
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
![Soft Green Modern Personal Branding Golden Rules Instagram Post](https://github.com/user-attachments/assets/d67e8d92-3961-4415-8eee-ebd168483363)

## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
## admin:
```
from django.contrib import admin
from.models import footballplayers,footballplayersAdmin
admin.site.register(footballplayers,footballplayersAdmin)
```
## model:
```
from django.db import models
from django.contrib import admin
class footballplayers(models.Model):
    Name=models.CharField(max_length=20)
    DOB=models.DateField()
    Height=models.IntegerField()
    Address=models.CharField(max_length=100)
    MobileNo=models.IntegerField()
class footballplayersAdmin(admin.ModelAdmin):
    list_display=["Name","DOB","Height","Address","MobileNo"]
```

# OUTPUT
Include the screenshot of your admin page.
![Screenshot 2024-12-07 202449](https://github.com/user-attachments/assets/a1a98a07-1c3e-4a5d-b1e3-d8410f3541af)


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
