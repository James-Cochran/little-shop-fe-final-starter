# Little Shop - Coupon Codes | Final Project | Frontend Starter Repo

This Vite Little Shop - Coupon Codes FE Final Project Boilerplate is built to consume and display the data from the BE Rails API built in the Mod 2 Final Project.  

## Set Up Instructions

**Note:** Do **not** clone this repo into your backend repo. Put it somewhere else as a stand alone. The BE and FE repos will remain two separate repos and you will submit the links to each.  

1. Fork repo
1. Clone forked repo and rename it `git clone <repo> <new name>`
1. `cd` into cloned repo
1. Run `npm install`
1. Run `npm run dev` to start developing.
  1. You'll see in the terminal that the project has opened at "http://localhost:5173/"

## Notes

This FE application is build to consume the data from your Rails API.  In order for it to work, you must have your Rails API running on localhost:3000. You will see fetch errors when running the FE without the BE API up and running.  

Follow the directions in the FE requirements portion of the Little Shop Coupon Codes final project spec. When you are finished with the FE work, update this README to remove the current content and follow the template below.  

______________________________________________________  
# README Template  
Before turning this project in, erase this line and everything above it and fill in the info below.  
______________________________________________________  

Back End
[GitHub]<https://github.com/James-Cochran/little-shop-be-final-starter>
Front End
[GitHub]<https://github.com/James-Cochran/little-shop-fe-final-starter>
[LinkedIn]<https://www.linkedin.com/in/james-cochran-/>

### Abstract:
I added functionality for merchats to be able to utalize coupons in their sales platform.  They are now able to track what coupons have been used, what invoices they are attached to, create new coupons, and activate/deactivate coupons.

### Installation Instructions:
1 - Start by cloning down two seperate repositories the back end and the front end using the links above.
2 - Navigate to the back end directory and install your dependencies first run bundle install, and then set up the database by running rails db:{drop,create}
then rails runner ActiveRecord::Tasks::DatabaseTasks.load_seed and finally rails db:migrate
3 - While the back end is running navigate into the front end directory and run npm run dev.
4 - Now that both back end and front end servers are running open a browser and visit http://localhost:5173


### Preview of App:


### Context:
This project was kicked off on a Thursday afternoon and was due the following Tuesday evening.
Using an existing back end API and implement new funcionality with the addition of coupon features. Then connect it to a front end application.

### Learning Goals:
Learning goals were to effecively use rails to create new data tables with relationships to existing tables.  These new tables should have clean and effective routing endpoints. Fully funtional and fully tested. And be able to display all the functions to the front end.

### Wins + Challenges:
This whole thing was a challenge, but I did it 
