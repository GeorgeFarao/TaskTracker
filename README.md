# Task Tracker Application
Task Tracker Web App using Angular

### Description
Using this app you can create a list of tasks, each one having a description, day & time and a reminder. Users can add and delete tasks and turn their reminder on and off by double clicking on a task in the list.
#
#### The app without the form to add tasks looks like this

![image](https://user-images.githubusercontent.com/41078921/149779120-2dbf3eb1-b44f-4a6f-8a2d-9ba5fdf2f0a0.png)

#### And with the form 

![image](https://user-images.githubusercontent.com/41078921/149779280-003ce9e5-1ac9-4bdf-ac33-06fddc79fdb6.png)

#### There is also a simple about page in the footer of the app

![image](https://user-images.githubusercontent.com/41078921/149779417-05858c34-5510-46c4-9a72-32fca90dccae.png)

#
The url for the app's index is http://localhost:4200/. You need to run ``ng serve`` first. For the backend, to store the tasks, I used json-server. <br>
To start the json-server run ``npm run server``. __server__ script is configured in package.json.
You can view the tasks stored using this link http://localhost:5000/tasks or through the __db.json__ file.
#
This app is based on the Angular Crash Course from Travercy Media on YouTube.

