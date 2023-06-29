<h1>Marketplace App</h1>

Welcome to the repository of this Marketplace app, built using Python, Django, and TailwindCSS.

This README provides detailed instructions on how to get this project up and running on your local machine for development and testing purposes.


<h2>Features of the marketplace app</h2>

<h3>1.  Log in and Sign up feature </h3>
<h3>2.  Add items </h3>
<h3>3.  Browse items </h3>
<h3>4.  Listed items </h3>
<h3>5.  Click item for more info </h3>
<h3>6.  More info contain, name,price,name of the seller and description </h3>
<h3>7.  Items categorised in 3 categories </h3>
<h3>8.  Search function </h3>
<h3>9.  Select category function </h3>
<h3>10. Clear all filters function </h3>
<h3>11. Dashboard with listed items of your user </h3>
<h3>12. Edit item when its your own listed item</h3>
<h3>13. Delete item</h3>
<h3>14. If not your item, can contact seller for information</h3>
<h3>15. Conversation</h3>
<h3>16. Messages between sellers </h3>
<h3>17. Inbox </h3>

<br>

<h2>Test users credentials</h2>

**username**: test1
<br>
**password**: test123456

<br>

**username**: test2
<br>
**password**: test234567


<br>


<h1>Prerequisites</h1>

The following software needs to be installed in your system:

Python 3.9 or newer [(https://www.python.org/downloads/)](url)

Git [(https://git-scm.com/downloads)](url)



<h1>Steps to Setup</h1>

<h3>1. Clone the repository</h3>

First, you will need to clone the repository using Git. Open your terminal and run the following command:

```
git clone https://github.com/tilspanos/ToDoApp.git
```

<h3>2. Create a virtual environment</h3>

If you are on MacOs always use <code>pip3</code> and <code>python3</code> to make sure that commands always work.

It is a good practice to create a virtual environment for your Python projects. This keeps dependencies required by different projects separate.


Navigate to the project directory:
```
cd ToDoApp
```

Create a virtual environment:
```
python3 -m venv env
```
Activate the virtual environment:

On macOS and Linux:
```
source env/bin/activate
```

On Windows:
```
.\env\Scripts\activate
```

<h3>3. Install dependencies</h3>

Next, install the project dependencies, which are listed in the requirements.txt file. In your terminal, run:
```
pip install -r requirements.txt
```

<h3>4. Apply the migrations</h3>

Django uses a database to store application data. So, before you can use the application, you need to create the database structure. This is done by running the following command:
```
python manage.py migrate
```
<h3>5. Run the server</h3>

Now, you're ready to start the development server:
```
python manage.py runserver
```

This will start the server at [http://127.0.0.1:8000](url). Open this URL in your browser.

<h3>6. Create a super user</h3>
To have access to the admin dashboard you must create a super user:

```
python manage.py createsuperuser
```




