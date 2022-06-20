# MyOnlineStore
A django-based e-commerce website designed for selling electronics. 

## Setting Up

**Development Environment**

To get this project up and running you should start by having Python installed on your computer. It's advised you create a virtual environment to store your projects dependencies separately. You can install virtualenv with

```
pip install virtualenv
```

Clone or download this repository and open it in your editor of choice. In a terminal (mac/linux) or windows terminal, run the following command in the base directory of this project

```
virtualenv env
```

That will create a new folder  `env`  in your project directory. Next activate it with this command on mac/linux:

```
source env/bin/active
```

Then install the project dependencies with
```
pip install -r requirements.txt
```

Now you can run the project with this command

```
python manage.py runserver
```


**Environment Variables**

Rename/Copy env.example as .env, and set up the environment variables in .env file. 

    cp .env.example .env

Note: The website uses SMTP to send  emails to the customers and therefore requires an email account for the functionality to work. Also requires a PayPal account for the payment functionality.
