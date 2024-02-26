# MERN-STACK-APPLICATION
## A To-do web application implementation on a MERN Stack 
This web applciation is deployed on an EC2 Instance/Virtual Server running on the AWS Cloud
![screenshot](./screenshots/ec2ubuntuserver.png)

- The MERN stack is a popular JavaScript stack which is used for building modern day web applications. MERN is an acronym that stands for: MongoDB, Express.js, React, Node.js

**MongoDB:** MongoDB is a NoSQL database that stores data in flexible, JSON-like documents. MongoDB is highly scalable, flexible, and easy to use. This makes it a popular choice for web applications that require handling data in a more dynamic and flexible way.

**Express.js:** Express.js is a flexible Node.js web application framework that provides a set of features for building web and mobile applications. Express.js uses its robust set of features to simplify the process of building web servers and handling HTTP requests.

**React:** React is a JavaScript library for building user interfaces (UI). It allows developers to create reusable (UI) components that efficiently updates and render data as it changes. React's component-based architecture and virtual DOM make it well-suited for building dynamic and interactive user interfaces.

**Node.js:** Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. It enables developers to run JavaScript code outside of a web browser, making it possible to build server-side applications using JavaScript. Node.js is highly efficient and scalable, making it a popular choice for building backend services in the MERN stack.
- ### Getting the location of Nodejs software from Ubuntu repositories 
curl is the command-line tool used to transfer data from or to a server. It is commonly used to download files or web pages from URLs.
This command downloads a script from NodeSource's website, which is responsible for setting up the Node.js 18.x repository on the system. The script is then executed with elevated privileges using sudo. This is a common way to install Node.js on Debian-based Linux distributions.
```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
```
![screenshot](./screenshots/repository-configured.png)

- ### Install Node.js
```
sudo apt-get install -y nodejs
```
The command above installs both nodejs and npm. NPM is a package manager for Node like apt for Ubuntu, it is used to install Node modules & packages and to manage dependency conflicts. 

```
node -v
```

the node -v command is used to verify the node installation/version of node.js installed on your machine

![screenshot](./screenshots/nodejs-installed.png)

___

- ### Application code setup: Create a new directory for your To-Do project
N/B: Directories are case sensitive Hence, "Todo" is not the same as "todo". 
```
mkdir Todo
```
N/B: After creating the Todo directory, run the ls command to verify that the Todo directory is created 
```
ls
```
![image](./screenshots/todo-directory.png)