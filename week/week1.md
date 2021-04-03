# Week 1

In this week, we will learn bout Django and make a sample app.

**Django** is a python based web framework i.e. we code our logic in python for displying(rendering) a HTML/CSS based web page.

### Install Django
We can install Django using pip. In cmd
```cmd
pip install django
```

Check your installation by

```
python -m django --version
```

Other installation process are available on Django [documentation](https://docs.djangoproject.com/en/3.1/topics/install/).

## Setup Your first project

Create a directory where you are gonna make your first project and go to that directory.
Now type following command to initiate a django project.

```python
django-admin startproject <project_name>
```

This will create a folder of name <project_name> and initialise django-template files in it. You can see those in the folder.

In cammand prompt, go to this project folder.

To start your local server, use following command in ./<project_name>

```
python manage.py runserver
```

Go to localhost link provided(my case, it is http://127.0.0.1:8000/) and you will see a django starter template!
Congratulation, you have setup your first project!

## Poll App
In this tutorial, we will build a poll app, with detailed instructions available on Django Documentation [here](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)

This tutorial is quite detailed(as expected, its a official tutorial). Try to go through and understand discription of every code, what it does. Try experimenting, dont just blindly copy code for sake of compleating the tutorial. This is a major resource, there is lots of help available on internet. You can just search your errors/doubts on google to get clarefied or can ask on whatsapp group.

At, the end of this tutorial, you will have basic knowledge of how django works.

This tutorial will take just 15min(if you blindly copy) to 2-hours. In your extra time, you can surf on internet and see what projects can be done on django and try watching one live coded project(30-45 min if you watch in x2 :p). Just search django on youtube and see how much is available.

### Extra Resources
- Check out Weak 5 and Week 6 of [Learners-Space Web Dev Course](https://github.com/wncc/learners-space/tree/master/Web%20Development)
- Week 6, [Back End Dovelopment CiQ](https://github.com/wncc/CodeInQuarantine/blob/master/Week_6_Backend/README.md)