# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram


## DESIGN STEPS

### STEP 1:

### STEP 2:

### STEP 3:



## PROGRAM
```
from django.db import models
from django.contrib import admin
# Create your models here.
class Laptop(models.Model):
    Productid= models.CharField(max_length=100,primary_key = True)
    Brandname = models.CharField(max_length=100)
    Modelname = models.CharField(max_length=80)
    Os = models.CharField(max_length=100)
    Colour = models.CharField(max_length=100)
    Price = models.IntegerField()

    
class LaptopAdmin(admin.ModelAdmin):
    list_display = ('Productid','Brandname','Modelname','Os','Colour','Price')
```
## OUTPUT
![Output](./django-orm-app/images/output.png)

## RESULT:
Thus we developed a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

