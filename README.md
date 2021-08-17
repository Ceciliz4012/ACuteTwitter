# Collaborators
Yuxuan Wang, Yiran Chen
# How to Run
To run the code, open it with pycharm or other editors. 
In the terminal, type: pipenv shell. 
Once you've entered a virtual environment equipped with django, do the following: python manage.py runserver. 
Once you do, clicked on the link that popped up and you will hit home and you can play around with it according to the webpages.
# Design
As you navigate through our twitter machine, first you will see a splash page. After click on CREATE ACCOUNT, users will be taken to a page where they can choose to sign up or login. There are certain requirements associated with creating a new account, and users will be prompted with warnings if they violate any requirement. After creating an account and logging in, users are directed to the home page, which has all the public posts. Some features include like, comment, create new post, view my post, and logout. 
The page is designed into two columns, with posts in the left column and HashTags in the right column. If hashtag is empty, the system will prompt you to create some tags. 


