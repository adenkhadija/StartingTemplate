Flask is a minimal Python framework that helps you create a web server. 

Let's take a look at the code we have:

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<h1>Hello, World!</h1>"
```
	
What did that code do?

First we `import` the `Flask` class. An instance of this class will be our WSGI application.

Next we create an instance of this class. The first argument is the name of the application’s module or package. `__name__` is a convenient shortcut for this that is appropriate for most cases. This is needed so that Flask knows where to look for resources such as templates and static files.

We then use the `route()` decorator to tell Flask what URL should trigger our function. In this case we use `/` routh, which is the default route of any website.

The function returns the message we want to display in the user’s browser. The default content type is HTML, so HTML in the string will be rendered by the browser.

Ideas on enhancements:
#Add to list
#Remove from list
#Remove multiple
#Visually check off items
#Login screen
#Important stuff indicator
#Add multiple things
#Notes section for the task
#View page for list
#Edit page for editing everything
#Loading indicator
#Give it some design flair
#Color code list entries
#Sorting
#Date field - prevent procrastination
#Prevent duplicates
#Recurring events
#Drag and drop list items
#Time estimation field
#Reminders

![image](https://user-images.githubusercontent.com/32689713/148437524-49ed9170-c625-407f-8d75-b065b7511b0c.png)


To learn more, checkout the [official guide](https://flask.palletsprojects.com/en/2.0.x/quickstart/).

Flask examples and tutorials
<https://replit.com/talk/learn/Flask-Tutorial-Part-1-the-basics/26272>

<https://www.fullstackpython.com/flask.html>

<https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates>


Methods for displaying form data and for styling flask applications
https://pythonprogramming.net/flask-bootstrap/
