# ToDO - Live ToDo Application

ToDo is a MEAN stack based web application Which helps to create To do's

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
 
1) To start with this, install node and npm

* [NodeJs](https://nodejs.org/en/) - Please refer for installing node

2) Install git 


* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) - Please refer for installing git

3) Use npm to install Angular CLI . Exceute this command

```
>npm install -g @angular/cli
```

 
### Installing/ Running locally


1) Create a folder named as todo-app at any local drive

2) change directory to todo-app

```
>cd todo-app
```

3) Fetch the source code from my github library
 
```
>git init
```

```
>git remote add origin https://github.com/jesccy/
```

```
>git pull origin master
```

4) Install all the modules that are required using

```
>npm install
```

5) Run the application using

```
>ng serve --open
```
6) Visit http://localhost:4200/ 


* [Demo](https://github.com/jesccy/todocode.git) - Please check demo here

## Screenshots of Application

### Login Page
![alt loginpage](https://github.com/jesccy/toDoApp/blob/master/screenshots/login.jpg)

### Sign Up Page
![alt signuppage](https://github.com/jesccy/toDoApp/blob/master/screenshots/signup.jpg)

### Single User Section
![alt singleuserpage](https://github.com/jesccy/toDoApp/blob/master/screenshots/single-user.jpg)

### Friends Section
![alt friendspage](https://github.com/jesccy/toDoApp/blob/master/screenshots/friends.jpg)


## More about the application

Application is having following views -


1) User management System -

    a) Signup - User is able to sign up on the platform providing all
details like FirstName, LastName, Email and Mobile number. Country
code for mobile number (like 91 for India) will be automatically selected after selecting the Country.

    b) Login - User is able to login using the credentials provided at signup.

    c) Forgot password - User can recover password using a link on email. 


2) To do list management (single user) -

    a) Once user logs into the system, he see an option to create a ToDo List
    b) User is able to create, a new empty list, by clicking on a create button
    c) User is able to add, delete and edit items to the list
    d) User is able to add sub-todo-items, as child of any item node.
    Such that, complete list will take a tree shape, with items and their
    child items.
    e) User is able to mark an item as "done" or "open".
    f) User is able to see his old ToDo Lists, once logged in.

3) To do List management (multi-user) -

    a) Friends are able to edit, delete, update the list of the user.
    b) On every action, all friends will get notification, in real time, of what specific
    change is done by which friend. Also the list should be in sync with all
    friends, at any time, i.e. all actions should be reflected in real time.
    c) Any friend is able to undo, any number of actions, done in past.
    Each undo action, will remove the last change, done by any user. So,
    history of all actions will be persisted in database , so as, not to
    lose actions done in past.
    d) Undo action will happen by a button on screen, as well as, through
    keyboard commands, which are "ctrl+z" for windows and "cmd+z" for mac.

4) Friend List -

    a) User is able to send friend requests, to the users on the
    system. Once requests are accepted, the friend will be added in user's
    friend list. Friends will be Notified, in real time using notifications.


5) Error Views and messages - Each major error response
(like 404 or 500) are handled by different pages.Like if user try to access the page that is not in the application he/she will get a 'Page Not Found Page'.


5) Documentation 

- All the APIs and Events are well documented using npm module apiDoc 

* [APIDOC](http://api.curiouswebs.in/apidoc/) - APIDOC of ToDo App backend.

## Built With

* [Angular](https://angular.io/) - The web framework used for Frontend Design
* [NPM](https://www.npmjs.com/) - Most of the modules are used
* [nodemailer](https://nodemailer.com/about/) - NPM module to send the mails
* [apiDoc](http://apidocjs.com/) - NPM module to create the apiDoc and eventDoc


## Authors

* **Jaspreet Kaur** - *Initial work* - [jaspreet](https://github.com/jesccy/)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for detailsg




