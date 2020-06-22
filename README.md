# Django_Blogapp
 
 This basic Django Blog app shows the basic features of a general blog based websites, where different users have their user profiles
 and can post iff they are registered user in database. Hence it gives the option for any user to register first and then login and post on 
 the blog home page.
 
 features : 
 1. Email and Password based profiles.
 2. Posts can be viewed as User view.(seeing post only from particular user).
 3. Email based password reset feature.
 4. Profile viewing(with username, Profile pic and email-address)
 
 Instructions :
 1. For running this django blog app, u need to have python installed in your machine.
 2. >install pip.
 3. Then create a virtual environment:
    a. >pip install virtualenv
    b. >pip install virtualenvwrapper-win
    c. >mkvirtual test
    
 #test is the name of virtual environment
 #Anything we install now will be specific to this project. And available to the projects we connect to this environment.
 
 4. for deativating virtual environment:
    >deactivate
 5. create your django root folder here:
    >mkdir root
    >cd root
 6. To again activate this environment use:
    >workon test
 7. Next, step is to install django:
    >pip install django
    #django will be installed for this particular environemnt not for whole machine.
 8. Now move to folder where manage.py is installed.
    >cd Blogapp
    # manage.py will be in this folder.
 9. Run:
    >python manage,py runserver
    # server will be runnig at localhost(http://127.0.0.1/8000)
 10. Go to Browser and type this IP in browser.
      you will be able to see blog app in your browser.
 
 
