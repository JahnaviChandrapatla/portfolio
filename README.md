# portfolio
Build a portfolio site using HTML & CSS that replicates the design mockup PDF-file. Develop a responsive website that will display images, descriptions and links to each of the portfolio projects that will be completed throughout the course of the Udacity's Front-End Web Developer Nanodegree.
However, students were permitted to implement custom changes to the design (colors, interactivity, etc) rather than fierce adherence to the design mockup.

Bootstrap was used for the design. Modals were implemented on the project images.

# Run this Project
Clone or download ZIP
Open states.html.


# Item Catalog project on TvStore
by Chandrapatla Jahnavi

## About
This project is of Udacity Full Stack Nanodegree. This Item Catalog project i.e., tvstore consists of developing an application that provides a 
list of tvlist within a variety of categories, as well as provide a gmailuser registration and authentication system. This project 
uses persistent data storage to create a web application that allows users to perform Login, Create, Read, Update, Delete and Logout 
operations.

User should generate an api key and credential key to connect to the gmail account.

A user does not need to be logged in order to read the tvcategories or items uploaded. However, gmailusers who created an item are the 
only users allowed to update or delete the item that they created.

This project uses third-party oauth with Google. Some of the technologies used to build this application include Flask, Bootsrap, 
Jinja2, and SQLite.

## Skills required for this project
Python
HTML
CSS
Bootstrap
Flask
Jinja2
SQLAchemy
OAuth
Google Login

## Tools required to run this project
Vagrant
VirtualBox
Udacity Vagrantfile

## Getting Started doing project
Install Vagrant and VirtualBox
Clone the Vagrantfile from the Udacity Repo
Download this zipfile and unzip this into the TvStore/ directory found in the Vagrant directory
Run vagrant up to run the virtual machine, then vagrant ssh to login to the VM
from the main directory run sudo pip install -r requirements
run application with python main1.py from within its directory
go to http://localhost/Televisions to access the application
*if first time running, you must add a category before adding an item

## JSON Endpoints
/Televisions/<path:tvlist_name>/tvs/JSON - Returns JSON of all items in TvStore
/Televisions/<path:tvlist_name>/<path:edition_name>/JSON - Returns JSON of selected item in TvStore
/Televisions/tvCatogories/JSON - Returns JSON of all categories in TvStore
/Televisions/JSON - To display allTvs in TvStore
/Televisions/tvs/JSON - To display all items in TvStore

## Operations performed
login,add,edit,update,delete,Logout

## Running the application
Run your application within the VM (python main1.py)
Access and test your application by visiting http://localhost:9494 locally
Testing whether the operations are working perfectly or not.




