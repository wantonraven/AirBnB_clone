# AirBnB_clone
![image](https://user-images.githubusercontent.com/49359467/218249127-90128127-1092-43c4-a612-bf8caa5f597c.png)
## Background Context

## Welcome to the AirBnB clone project!
Before starting, please read the AirBnB concept page.

<iframe width="560" height="315" src="https://www.youtube.com/embed/XRH_8w1DEGI" title="SE - HBNB project overview" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## First step: Write a command interpreter to manage your AirBnB objects.
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

* put in place a parent class (called <code>BaseModel</code>) to take care of the initialization, serialization and deserialization of your future instances
* create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
* create all classes used for AirBnB (<code>User</code>, <code>State</code>, <code>City</code>, <code>Place</code>…) that inherit from <code>BaseModel</code>
* create the first abstracted storage engine of the project: File storage.
* create all unittests to validate all our classes and storage engine

![image](https://user-images.githubusercontent.com/49359467/218249008-ec46bfd0-7bff-4a77-8510-a6068dd3e60f.png) 

## What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

* Create a new object (ex: a new User or a new Place)
* Retrieve an object from a file, a database etc…
* Do operations on objects (count, compute stats, etc…)
* Update attributes of an object
* Destroy an object
* learning to create AirBnB_clone console with testcases

## Resources
* <a href="https://intranet.alxswe.com/rltoken/8ecCwE6veBmm3Nppw4hz5A">cmd module</a>
* <a href="http://pymotw.com/2/cmd/">cmd module in depth</a>
* <b>packages</b> concept page
* <a href="https://docs.python.org/3.8/library/uuid.html">uuid module</a>
* <a href="https://docs.python.org/3.8/library/datetime.html">datetime</a>
* <a href="https://docs.python.org/3.8/library/unittest.html#module-unittest">unittest module</a>
* <a href="https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/">args/kwargs</a>
* <a href="https://www.pythonsheets.com/notes/python-tests.html">Python test cheatsheet</a>
* <a href="https://wiki.python.org/moin/CmdModule">cmd module wiki page</a>
* <a href="https://realpython.com/python-testing/">python unittest</a>

## Learning Objectives
At the end of this project, you are expected to be able to <p style="color:red;">explain to anyone<p>, without the help of Google:

## General
* How to create a Python package
* How to create a command interpreter in Python using the cmd module
* What is Unit testing and how to implement it in a large project
* How to serialize and deserialize a Class
* How to write and read a JSON file
* How to manage datetime
* What is an UUID
* What is *args and how to use it
* What is **kwargs and how to use it
* How to handle named arguments in a function

## Copyright - Plagiarism
* You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
* You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
* You are not allowed to publish any content of this project.
* Any form of plagiarism is strictly forbidden and will result in removal from the program.
* This project is the first step towards building a full web application: the AirBnB clone.

## Requirements
The console or command interpreter create the data model and allows create, update, destroy, store and persist objects to a file (JSON file). This console will be a tool to validate this storage engine..
