CREATE DATABASE <dbname> CHARACTER SET utf8;
ALTER DATABASE bookbank CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
ALTER DATABASE bookbank CHARACTER SET utf8 COLLATE utf8_general_ci;

ALTER DATABASE bookbank CONVERT TO CHARACTER SET utf8 COLLATE utf8_general_ci;

ALTER TABLE product_author CONVERT TO CHARACTER SET utf8 COLLATE utf8_general_ci;
ALTER TABLE product_author CONVERT TO CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

Vinasave@123
ALTER DATABASE bookbank CHARACTER SET 'utf8' COLLATE 'utf8_unicode_ci';



1. cài đặt Django: pip3 install Django | Cài rest: pip3 install djangorestframework
------------------------
2. tạo site: django-admin startproject mysite 
------------------------
3: cd mysite //tro dem thu muc
-------------------------------
4: python manage.py runserver // Chay server file manage.py
-----------------------------------
5: python manage.py startapp product //Taoj 1 app m
//--------------------
python manage.py makemigrations
python manage.py migrate
//-- Tạo supper admin
python manage.py createsuperuser
//-------------------------------
Giao diện suit Admin
pip3 install django-suit
pip3 uninstall django-suit
pip3 install https://github.com/darklow/django-suit/tarball/v2
//------------------------
Vinasave@123
sudo mysql -u root -p
//-------------------------------------------------
