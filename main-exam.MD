**African UNiversity of Benin**
_first semester examination_
_300L 2022 jan 18_



You are required to to build a full fetured web application with the django web framewrok 

the app youre are required to build is a "TODO App"

this app collects input data and displays it on the screen for the user, 

*Data ase Models*

your database model should have the following fields

1. name of todo
2. data todo was created
3. Completed/not completed (thei field recieves a true/false value of the todo has been completed.
4. all data inthe databse must be gotten from ModelNAme.objects.all()


**views**

use function based views for all your views



**form(optional)**

you can read the django documentation and imlemment for views



freehands(what i expect)

Google is a tool and i expect you to search for solution to your problrms and not the exact solution to the question

i have an algorithm to check and kmow if code was copied from the intetnet so mind you if such is detected i would commit you code as null and void


**how to submit**

you are required to pudh your code to your guthub ccount using git

steps are as follows

1. creare a git repository on github.com
2. cd into your project from your command prompt/terminal and write the followinf codes
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jephthah-snr/aub-exam.git   {i used my own repository as example, you have to point the url to ypur own repo}
git push -u origin main


you file will be aded to your github repo sucessfully.



write the iink to your repo in your exam paper and submit it.


code snippets have been provided for you [here] (ttps://github.com/jephthah-snr/aub-exam-snippets.git) the contain html / css/ js files for your consumption.



good luck and see you at the other side.



*django requirements. you can add these to a req.txt file and run "pip install -r req.txt"*

asgiref==3.4.1
dj-database-url==0.5.0
Django==3.2.7
django-crispy-forms==1.13.0
django-heroku==0.3.1
gunicorn==20.1.0
Pillow==8.4.0
psycopg2==2.9.1
pytz==2021.1
sqlparse==0.4.2
whitenoise==5.3.0
