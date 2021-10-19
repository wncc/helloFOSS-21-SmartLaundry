# Hello-FOSS-21-SmartLaundry

This project is a part of HELLO-FOSS: Celebration of Open Source by the Web and Coding Club. In this project we will be using flutter to create an application which aims to solve the problem of washing machine management in hostels.

## Guidelines
To contribute to this project there are not many prerequisites just that you should have basic programming knowledge including OOPs. You can go through [these resources](https://tinyurl.com/smartlaundryresources) if you want to learn or revise any of the concepts.

## SmartLaundry - No more chaos in hostels
Washing your clothes in a propper manner in hostels is a big deal. It is very difficult to find a free washing machine in a hostel having 10 floors. But, the problem doesn't end here, even you got a free washing machine, you'll have to remember that your clothes are in it, otherwise someone will throw them out, or will wait for a long time.

This app is an attempt to solve this problem, and to see if we can manage the washing machines in the hostels efficiently with an app. This is the best time for it to be created as people are contributing to open source and their minds are filled with creative ideas. This is also helping beginners to learn and start contributing.

## The Application
### Frontend
The frontend of the app is to be written in flutter in order to make it cross-platform. You can find the User Interface of the app [here](https://tinyurl.com/smartlaundryui). This is the basic idea of the user interface which is to be inplemented in the app. You are open to change the UI and think of some more elements which can be added to make the app more useful, or you can create a new one if you want.

**Description of the activities in the app** - 
* **Login/Signup** - Screens of loggin in and signing up for the app
* **Status** - Screen showing the status of all the washing machine on each floor of the hostel
* **Individual Status** - Details of a washing machine
* **Add Clothes** - Input time when adding clothes in a washing machine

You can also add new screens if you want more features to be implemented.

### Backend
We have planned to use Firebase as the backend of the application, due to its simplicity and compatibility. Anyone can create a firebase project and test his/her apps on it. We have given the basic structure of the backend database design, again, you are free to change/use your own if you feel it is more efficient.

We implementing the following features
* Using realtime database to store the details of the washing machines
* Using authentication to create accounts and verify them

**Details of the design -** There are two main branches, **hostels** and **users**. **hostels** have the data of all the hostels with all the machines on each of their floors. **users** have the data of all the users registered on the app. Each machine is given an ID relating it to its hostel and floor, and have children 
* **status** - status BUSY/FREE 
* **time_left** - time left till it becomes free
* **user** - ldap of user if it is busy

Each **user** branch is having children corresponding to the details of the registered users like
* **name** - name of the user
* **mobile** - mobile number of the user
* **hostel** - residing hostel of the user
* **room** - room number

You can also add new details if you want more features to be implemented.

## Resources
All the resources and other links can be found at [this page](https://tinyurl.com/smartlaundryresources).
