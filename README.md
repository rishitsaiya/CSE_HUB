# CSE-HUB

Based on [php version](https://github.com/harshraj22/contest)

##### Idea :
To have a website that caters all needs that a CSE UG has.

##### What works ?

* adding problems (login_required)
* adding testcase (for now we can only add one test case at a time, also only author of a problem can add testcase for the problem)
* login/logout
* adding solution (checks if user is logged in or not)
* evaluation of solution
* updation of table for problems upon adding solution by the user(successful/total submissions)
* adding predefined tags to problems

##### What lacks ?

* Only mode of submission is through file upload
* No work is done for uploading a contest
* frontend
* Display all solutions by a user and for a question
* Editing of profile/ problem/ added testcase
* User registration (signUp)

##### Mapped urls :

* ```admin/```
* ```''```
* ```profile/<username>```
* ```problems/add```
* ```problems/display/<int:problem_id>```
* ```problems/add/testcase```
* ```problems/submit/<int:problem_id>```
* ```problems```
* ```login```
* ```logout```

##### Installation :

* create a virtual environment and activate it (google it)
* Install dependencies into it ```pip3 insall -r requirements.txt```.
* Make sure if you are using virtual environment, you have all dependencies installed (mentioned in ```requirements.txt```). ```python3 manage.py migrate --run-syncdb ``` [read here](https://stackoverflow.com/a/37799885/10127204), ```python3 manage.py makemigrations``` and ```python3 manage.py migrate```. This will update database with tables as we describe in models.py. Then ```python3 manage.py runserver``` and play around testing what all has been developed.

##### Screenshots :
![Screenshot from 2019-12-04 02-29-03](https://user-images.githubusercontent.com/46635452/70089367-f0fab600-163d-11ea-81d9-fa1441ac95ac.png)

![Screenshot from 2019-12-04 03-31-38](https://user-images.githubusercontent.com/46635452/70093670-ed1f6180-1646-11ea-9b39-3c318603edbe.png)

