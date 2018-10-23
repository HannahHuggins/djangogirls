# Djangogirls blog

This is a blog i've created using a Python and Django tutorial on https://tutorial.djangogirls.org/en/. 

## How to run

* Open the terminal and change into the **djangogirls** directory `cd djangogirls`

* Next you need to make a **virtual environment**, so create a folder within the djangogirls directory using the **terminal**. `python3 -m venv myvenv`

You can then start the virtual environment by typing 
`source myvenv/bin/activate`

* Install **Django** (make sure you have the latest version of **pip**) 
`python3 -m pip install --upgrade pip`

* Run the **web server**
`python manage.py runserver`

* Go to - http://127.0.0.1:8000/admin/

* Create a **superuser** to log into the account
`python manage.py createsuperuser`



