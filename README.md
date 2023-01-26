# Python-Class-125

Pip3 install -U scikit-learn


https://realpython.com/the-model-view-controller-mvc-paradigm-summarized-with-legos/

A user requests to view a page by entering a URL.
The Controller receives that request.
It uses the Models to retrieve all of the necessary data, organizes it, and sends it off to the…
View, which then uses that data to render the final webpage presented to the the user in their browser.



When you type in a URL in your browser to access a web application, you’re making a request to view a certain page within the application.

When building a web app, you define what are known as routes. Routes are, essentially, URL patterns associated with different pages. So when someone enters a URL, behind the scenes, the application tries to match that URL to one of these predefined routes.

So, in fact, there are really four major components in play: routes, models, views, and controllers.

Routes
Each route is associated with a controller - more specifically, a certain function within a controller, known as a controller action. So when you enter a URL, the application attempts to find a matching route, and, if it’s successful, it calls that route’s associated controller action.

Models and Controllers
Within the controller action, two main things typically occur: the models are used to retrieve all of the necessary data from a database; and that data is passed to a view, which renders the requested page. The data retrieved via the models is generally added to a data structure (like a list or dictionary), and that structure is what’s sent to the view.


Views
Finally, in the view, that structure of data is accessed and the information contained within is used to render the HTML content of the page the user ultimately sees in their browser.

Summary
So a more detailed, technical summary of the MVC request process is as follows:

A user requests to view a page by entering a URL.
The application matches the URL to a predefined route.
The controller action associated with the route is called.
The controller action uses the models to retrieve all of the necessary data from a database, places the data in an array, and loads a view, passing along the data structure.
The view accesses the structure of data and uses it to render the requested page, which is then presented to the user in their browser.
