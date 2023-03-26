# Blogs-Django
blog website using django framework also provided admin panel , where you can control , write and modify blogs ..



### To run this Project 

1. clone into your local machine :  ``` git clone https://github.com/TejasP07/Blogs-Django.git```
2. go to project using ```cd django_blog```
3. go to inside folder ```cd django_blog ```
4. now to install and activate virtual environment type command : ``` pipenv shell```
5. Now install django to your inside the virtual environment : ``` pipenv install django ```
6. Now run this project using : ```python manage.py runserver ``` 
7. head over to http://127.0.0.1:8000/ to see the output
8. You will see the following output window : 
![django](https://user-images.githubusercontent.com/88932277/227762607-0851bc36-b58a-43eb-9468-b2e1edd8ee7b.PNG)
### Now you only see the blog but you will not able to write or modify or delete . 

for that you need to access the admin , for this you need to create a superuser and provided the login information and login ..

1. to create a super user run ``` python manage.py createsuperuser```  
3. This will ask you  

                      username :  
                      password :                    
                      Email :
                      
3. run again ```python manage.py runserver ```

4. Now to go http://127.0.0.1:8000/admin/ and login with your username and password .

5. output : ![Window](https://user-images.githubusercontent.com/88932277/227762537-3838dc87-1db0-4ce1-829a-496c52dc981c.PNG)
Now you can add blog , delete and update the blog posts..
 
 
 ##Thank You
for any query connect to linkedin https://www.linkedin.com/in/tejas-pawar7/


